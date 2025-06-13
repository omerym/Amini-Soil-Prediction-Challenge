# Amini Soil Prediction Challenge Solution

## Competition Overview
[Zindi Africa Competition Link](https://zindi.africa/competitions/amini-soil-prediction-challenge)  

## Data Preparation
1. **Download datasets** from the [competition data page](https://zindi.africa/competitions/amini-soil-prediction-challenge/data)
2. **Organize files**:
   - Create an `earth data` folder containing all earth observations csv files
   - Place `Train.csv` and `Test.csv` in the main project folder
  
## Execution Workflow
1. **Enhance datasets**:
   - Run `add earth data.ipynb` to create:
     - `train_earth.csv` (training data with earth features)
     - `test_earth.csv` (test data with earth features)

2. **Model training**:
   - Execute `notebook.ipynb` to:
     - Load enhanced datasets
     - Train machine learning models
     - Generate competition submissions
