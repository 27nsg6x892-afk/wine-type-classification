# Wine Type Classification

## Overview
This project classifies wine type as either red wine or white wine using chemical features from the Wine Quality dataset.

The project compares dimensionality reduction and classification methods, including PCA, LDA, and SVM with an RBF kernel. A strong part of the project is that it includes both from-scratch implementations and sklearn implementations, which helps validate the manual algorithm logic.

## Objectives
- Classify wine type as red or white
- Clean and prepare the dataset
- Apply exploratory data analysis
- Use PCA for dimensionality reduction and visualization
- Implement LDA from scratch and compare it with sklearn LDA
- Implement SVM with RBF kernel from scratch and compare it with sklearn SVM
- Evaluate models using accuracy and confusion matrices

## Dataset
The project uses the Wine Quality dataset.

Dataset details:
- Rows before cleaning: 6,497
- Columns before cleaning: 13
- Numerical features used: 12
- Target variable: wine type
- Missing values: 0
- Duplicate rows removed: 1,177
- Rows after removing duplicates: 5,320
- Train/test split: 80% training and 20% testing

Note: The full dataset may be excluded from this repository because of file size or usage limitations. A small sample can be included to show the expected data structure.

## Methods Used
- Data cleaning
- Duplicate removal
- Label encoding
- Stratified train/test split
- StandardScaler
- Outlier clipping
- Exploratory Data Analysis
- PCA from scratch
- sklearn PCA
- LDA from scratch
- sklearn LDA
- SVM with RBF kernel from scratch
- sklearn SVM
- Confusion matrix analysis

## Results

### LDA Results
- Scratch LDA accuracy: 99.62%
- sklearn LDA accuracy: 99.53%

### SVM Results
- Scratch SVM RBF accuracy: 99.44%
- sklearn SVM RBF accuracy: 99.53%

The best result was achieved by the from-scratch LDA model with 99.62% accuracy.

## Tools & Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

- ## How to Run

 Clone the repository:
git clone https://github.com/27nsg6x892-afk/wine-type-classification.git
pip install -r requirements.txt
jupyter notebook wine_type_classification.ipynb

## Project Status

Completed as an academic Pattern Recognition project.

## Author

Mark Samy Sabry

## Repository Structure
```text
wine-type-classification/
│
├── wine_type_classification.ipynb
├── Wine_Quality_Project_Report.pdf
├── requirements.txt
├── README.md

