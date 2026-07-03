# m2k2dc - Radiosonde Data Processing Project

## Project Overview
This project is designed for processing and analyzing radiosonde (weather balloon) data.

## Directory Structure
```
m2k2dc/
├── data/                 # Raw and processed data files
│   ├── raw/              # Original radiosonde data
│   └── processed/        # Cleaned and processed data
├── src/                  # Source code
│   ├── __init__.py
│   ├── data_loader.py    # Load radiosonde data from various formats
│   ├── processor.py      # Data processing and cleaning functions
│   ├── analyzer.py       # Analysis and visualization functions
│   └── utils.py          # Utility functions
├── tests/                # Unit tests
│   ├── __init__.py
│   ├── test_data_loader.py
│   ├── test_processor.py
│   └── test_analyzer.py
├── docs/                 # Documentation
├── requirements.txt      # Python dependencies
├── README.md             # Project overview
└── .gitignore            # Git ignore rules
```

## Features
- Load radiosonde data from common formats (CSV, JSON, NetCDF)
- Data cleaning and quality control
- Atmospheric profile analysis (temperature, humidity, pressure vs altitude)
- Visualization tools for sounding plots
- Statistical analysis of atmospheric conditions

## Getting Started
1. Install dependencies: `pip install -r requirements.txt`
2. Place raw data in `data/raw/`
3. Run processing scripts in `src/`
4. Find processed data in `data/processed/`

## Dependencies
- pandas
- numpy
- matplotlib
- netCDF4 (if working with NetCDF files)
- scipy

## Usage Examples
See examples in the `src/` directory or run the test suite to understand functionality.