# Data Preprocessing for Linear Regression

## Overview

This project demonstrates the basic data preprocessing steps required before building a Linear Regression model. The California Housing dataset from Scikit-learn is used for this project.

## Dataset

- Dataset: California Housing
- Source: Scikit-learn
- Number of Records: 20,640
- Features: 8
- Target Variable: HouseValue

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Preprocessing Steps

1. Imported the required libraries.
2. Loaded the dataset.
3. Displayed the dataset information.
4. Checked the number of rows, columns, and data types.
5. Checked for missing values.
6. Removed duplicate records.
7. Detected outliers using the IQR method.
8. Removed outliers.
9. Applied feature scaling.
10. Performed correlation analysis.
11. Displayed the correlation heatmap.
12. Converted data types where needed.
13. Cleaned column names.
14. Split the dataset into training and testing sets.
15. Built a Linear Regression model.
16. Evaluated the model using Mean Squared Error (MSE) and R² Score.
17. Saved the cleaned dataset.

## Files

- `data_preprocessing.ipynb` – Google Colab notebook
- `cleaned_dataset.csv` – Processed dataset
- `README.md` – Project description

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run each cell in order.
3. The cleaned dataset will be generated automatically.
4. The Linear Regression model will be trained and evaluated.

## Results

- Dataset was cleaned and prepared.
- Outliers were detected and handled.
- Features were scaled.
- The dataset was split into training and testing data.
- A Linear Regression model was successfully trained and tested.

## Conclusion

This project shows the basic preprocessing steps that improve data quality before applying a Linear Regression model. These steps help in building a more reliable and accurate machine learning model.

## Author

Rashmi Sinha
B.Tech Computer Science and Engineering
TKM College of Engineering
