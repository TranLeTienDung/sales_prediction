# sales_prediction
# Sales Forecasting Competition

## Team Information
- **Team name:** Your Team Name
- **Members:**
  - Member 1
  - Member 2
  - Member 3

---

## Project Overview
This project focuses on forecasting **Revenue** and **COGS** for future dates using machine learning and time-series forecasting techniques.

### Models Used
- Ridge Regression
- LightGBM
- Prophet
- Ensemble Blending

### Feature Engineering
The project includes:
- Calendar-based features
- Fourier seasonal features
- Vietnam holidays and Tet events
- Promotion schedule features
- Lag features
- Rolling statistics

---

## Repository Structure

```bash
.
├── README.md
├── data/
│   ├── sales.csv
│   └── other_data_files.csv
└── src/
    ├── features.py
    ├── train.py
    ├── predict.py
    └── model.ipynb
```

### Folder Description

#### `data/`
Contains raw datasets used for training and prediction.

#### `src/`
Contains source code:
- `features.py`: feature engineering pipeline
- `train.py`: model training scripts
- `predict.py`: inference and submission generation
- `model.ipynb`: Kaggle notebook experiments

---

## Requirements

Recommended Python version:

```bash
Python 3.10+
```

Install required packages:

```bash
pip install -r requirements.txt
```

Main libraries:
- pandas
- numpy
- scikit-learn
- lightgbm
- prophet

---

## How to Reproduce Results

### 1. Train models

Run:

```bash
python src/train.py
```

This script will:
- build features
- train Ridge model
- train LightGBM model
- train Prophet model
- perform ensemble blending

---

### 2. Generate predictions

Run:

```bash
python src/predict.py
```

Prediction outputs will be generated automatically.

---

## Output
Generated files include:
- Revenue forecast
- COGS forecast
- Submission CSV

---

## Notes
- This repository is set to **public** for evaluation.
- Raw data is included in the `data/` directory.
- Experiments were originally developed on Kaggle Notebook and synchronized to this repository.
