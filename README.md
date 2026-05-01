# sales_prediction
# Sales Forecasting Competition

## Team Information
- **Team name:** Tứ Hành Xung
- **Members:**
  - Trần Lê Tiến Dũng
  - Phan Quốc Tiến
  - Nguyễn Phúc Tâm
  - Nguyễn Trần Như Nguyệt
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
    ├── sales_prediction.ipynb
```

### Folder Description

#### `data/`
Contains raw datasets used for training and prediction.

#### `src/`
Contains source code:
- sales_prediction.ipynb: all code of the competition

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
- Pandas
- Numpy
- Scikit-learn
- Lightgbm
- Prophet

---

## How to Reproduce Results

### 1. Train models

Run:

```bash
python src/sales_prediction_ipynb
```

This script will:
- Build features
- Train Ridge model
- Train LightGBM model
- Train Prophet model
- Perform ensemble blending

---

### 2. Generate predictions

Run:

```bash
python src/sales_prediction.ipynb
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
