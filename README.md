# Breast Cancer Diagnostic Predictor 

## Project Overview
This project applies Machine Learning techniques to predict breast cancer diagnosis (Malignant vs. Benign) based on features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.

## Dataset
* **Source:** Kaggle (Breast Cancer Wisconsin Diagnostic Data)
* **Features:** 30 numeric features (Radius, Texture, Perimeter, Area, Smoothness, etc.)
* **Target:** Diagnosis (M = Malignant, B = Benign)

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Model:** Logistic Regression

## Key Results
* **Accuracy:** ~95% (Varies slightly based on random seed)
* **Confusion Matrix:** Successfully minimized False Negatives, which is critical for medical applications.

## How to Run
1.  Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2.  Run all cells to load data from the Kaggle mirror and train the model.
