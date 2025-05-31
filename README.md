# Steel Plate Faults Dataset (Augmented)
This repository contains the **augmented dataset** used for the paper:  
**“Building Fault-Specific Decision Trees for Quality Control in Steel Plate Manufacturing through Machine Learning Approach.”**

## Dataset Origin
- Original Dataset:  
  Steel Plates Faults dataset from the UCI Machine Learning Repository  
  Link: https://archive.ics.uci.edu/ml/datasets/Steel+Plates+Faults  
  Additional reference:  
  Dulinskas, O., n.d. Steel plate defect prediction. Available at: https://github.com/orestasdulinskas/steel_plate_defect_prediction  

## Dataset Description
- **File:** `Augmented_dataset.csv`  
- **Features:**  
  - LogOfAreas  
  - Log_X_Index  
  - Outside_X_Index  
  - Pixels_Areas  
  - X_Perimeter  
  - Sum_of_Luminosity  
  - Length_of_Conveyer  
  - SigmoidOfAreas  
  - Minimum_of_Luminosity  
  - Edges_Index  
- **Target Variable:**  
  - Fault_Type
## Fault Types
The **Fault_Type** column indicates the specific type of defect for each record. The fault types included in the dataset are:
- Pastry  
- Z_Scratch  
- K_Scatch  
- Stains  
- Dirtiness  
- Bumps  
- Other_Faults  
- No_Fault  
These labels provide a comprehensive representation of typical steel plate manufacturing faults.
- **Preprocessing:**  
  - Oversampling techniques applied to balance class distribution  
  - Standard feature scaling  
  - Data cleaning for missing and outlier values  

## Usage
Use the dataset for training and evaluating machine learning models for fault classification in steel plate manufacturing.

## Citation
If you use this dataset or related scripts, please cite appropriately. 
