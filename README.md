# PHMSA Data Analysis Project

This project analyzes data from the Pipeline and Hazardous Materials Safety Administration (PHMSA).

## Project Structure

```
PHMSA_DA/
├── data/               # Data files
│   ├── raw/           # Original, immutable data dump
│   ├── processed/     # Cleaned, processed data
│   └── external/      # Data from third party sources
├── notebooks/         # Jupyter notebooks
├── src/              # Source code
│   ├── data/         # Scripts to download or generate data
│   ├── features/     # Scripts to turn raw data into features
│   └── visualization/# Scripts to create visualizations
├── tests/            # Unit tests
└── docs/             # Documentation
```

## Setup

1. Create a new conda environment:
```bash
conda create -n phmsa_da python=3.6
conda activate phmsa_da
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Place raw data files in the `data/raw` directory
2. Run data processing scripts from `src/data`
3. Generate features using scripts in `src/features`
4. Create visualizations using scripts in `src/visualization`
5. Use Jupyter notebooks in the `notebooks` directory for exploratory analysis

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request

## License

[Add your license information here]