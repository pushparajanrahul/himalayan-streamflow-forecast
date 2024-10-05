# Himalayan Weather Prediction Project

## Overview
This project implements a multi-station weather prediction model for the Himalayas, utilizing LSTM and Transformer architectures to process time-series data from multiple weather stations and satellite sources.
Features

- Multi-station weather prediction
- LSTM and Transformer model architectures
- Comprehensive data preprocessing pipeline
- Custom evaluation metrics
- Interactive visualizations

## Data
The project uses data from various sources including:

- TRMM (Tropical Rainfall Measuring Mission)
- CHIRPS (Climate Hazards Group InfraRed Precipitation with Station data)
- ERA5 (ECMWF Reanalysis v5)
- Local weather station data

## Installation
```
bashCopygit clone https://github.com/your-username/himalayan-weather-prediction.git
cd himalayan-weather-prediction
pip install -r requirements.txt
```

## Usage
```
pythonCopypython train_model.py
python evaluate_model.py
python visualize_results.py
Model Architecture
```

LSTM Model: Multi-layer LSTM with dropout for sequence modeling
Transformer Model: Custom implementation with positional encoding and multi-head attention

## Evaluation Metrics

Standard: MAE, RMSE
Hydrological: NSE (Nash-Sutcliffe Efficiency), FHV, FMS, FLV

## Results

Achieved up to 0.8 NSE score for streamflow prediction
Detailed performance metrics available in results/ directory

## Visualizations

Interactive time-series plots using Plotly
Comparative bar charts for model performance using Matplotlib

