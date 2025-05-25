# Smart Water Anomaly Detection

This project aims to detect anomalies in smart water systems using data-driven techniques. The workflow includes data exploration, feature engineering, model training, evaluation, and anomaly detection.

## Project Structure


```
smart_water_anomaly_detection/
├── config.yaml                # Configuration file for parameters
├── README.md                  # Project overview
├── requirements.txt           # Python dependencies
├── data/
│   ├── raw/                   # Original dataset (do not commit large or sensitive files)
│   │   └── london_smart_meters_dataset_without_missing_values.tsf
│   └── processed/             # Cleaned and transformed data
├── models/                    # Saved models (Pickle or joblib files)
├── notebooks/
│   ├── data_exploration.ipynb
│   ├── feature_engineering.ipynb
│   ├── modeling.ipynb
│   ├── evaluation.ipynb
│   └── anomaly_detection.ipynb
├── outputs/
│   ├── figures/               # Plots and graphs
│   └── reports/               # Summary reports and evaluation metrics
├── src/
│   ├── data_loader.py         # For loading datasets
│   ├── preprocess.py          # Cleaning and preprocessing functions
│   ├── features.py            # Feature extraction and engineering
│   ├── model.py               # Model training and saving
│   ├── detect.py              # Anomaly detection logic
│   └── utils.py               # Helper functions
```

## Notes
- The `data/raw/` and `data/processed/` folders are ignored by git (see `.gitignore`). Place your datasets here, but do not commit large or sensitive files.
- The `models/` and `outputs/` folders are also ignored by git. Use these for model artifacts and generated results.
- Notebooks and source code are tracked by git.

## Setup

1. Create and activate a virtual environment:
   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```

## Usage

Run the notebooks in order for a complete workflow, or use the scripts in `src/` for modular tasks.

## License

MIT License

## Setup

1. Create and activate a virtual environment:
   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```

## Usage

Run the notebooks in order for a complete workflow, or use the scripts in `src/` for modular tasks.

## License

MIT License
