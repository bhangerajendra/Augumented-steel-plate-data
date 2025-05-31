# Steel Plate Faults Dataset (Augmented and Balanced)

This repository contains the **augmented and balanced dataset** used for the paper:  
**“Building Fault-Specific Decision Trees for Quality Control in Steel Plate Manufacturing through Machine Learning Approach.”**

## Dataset Origin

- Original Dataset:  
  Steel Plates Faults dataset from the UCI Machine Learning Repository  
  Link: https://archive.ics.uci.edu/ml/datasets/Steel+Plates+Faults  
  Additional reference:  
  Dulinskas, O., n.d. Steel plate defect prediction. Available at: https://github.com/orestasdulinskas/steel_plate_defect_prediction  

## Dataset Description

- **File:** `Augmented_dataset.csv`  
- **Rows:** [add number of rows here]  
- **Columns:** [add number of columns here, e.g., 27 features + 1 target variable]  
- **Preprocessing:**  
  - Oversampling techniques applied to balance class distribution  
  - Standard feature scaling  
  - Data cleaning for missing and outlier values  

## Usage

1. Download `Augmented_dataset.csv` and load it in Python or your preferred ML environment.
2. Example code to load the dataset using pandas:

    ```python
    import pandas as pd

    data = pd.read_csv('Augmented_dataset.csv')
    print(data.head())
    ```

3. Use the dataset for training and evaluating machine learning models for fault classification in steel plate manufacturing.

## Citation

If you use this dataset or related scripts, please cite appropriately. 
