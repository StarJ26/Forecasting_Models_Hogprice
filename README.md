# Hog Price Forecasting with Expanding Window (8 Models)

This repository implements **8 expanding window forecasting models** for hog price futures using `Hogprice` as the target.

## Models:
- LSTM (PyTorch)
- WAA-TFT (PyTorch)
- XGBoost
- LightGBM
- WAA-LightGBM
- TPE-LightGBM
- BO-LightGBM
- RS-LightGBM

## Usage:
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Place your raw data in `data/raw data.csv`.
3. Run all models:
```bash
python batch_run.py
```

## Output:
- Plots in PNG
- Forecast results in Excel
- Optimized hyperparameters in JSON

Ready for GitHub upload and batch evaluation for forecasting experiments.
