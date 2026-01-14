<div align="center">
<h1>Diabetes Prediction: Random Forest vs MLP</h1>
<em>This project implements and compares two machine learning models, <b>Random Forest</b> and <b>Multi-Layer Perceptron (MLP)</b>, to predict the presence of diabetes in patients. The analysis uses a comprehensive clinical dataset with 8 input features and 1 target variable. The system focuses on reliable classification, evaluated through rigorous Stratified K-Fold validation and metrics like Accuracy, Recall, and AUC.</em>
</div>

---

## Repository Contents

* **`Artificial_Intelligence_Project.ipynb`**: The Google Colab notebook containing the full pipeline: data preprocessing, visualization, model training (Random Forest & MLP), hyperparameter optimization, and final evaluation.
* **`Artificial_Intelligence.pdf`**: The detailed project report describing the methodology, theoretical background, and in-depth analysis of the results.
* **`diabetes.csv`**: The dataset used for training and testing. It contains clinical features (such as Age, BMI, Blood Pressure) collected from 2000 patients.

## Project Highlights

* **Methodology**:
    * **Data Splitting**: 80/20 Stratified Train-Test split to preserve class distribution.
    * **Preprocessing**: Standard Scaling (fitted on training data to prevent data leakage).
    * **Validation**: 5-Fold Stratified Cross-Validation used during Hyperparameter Tuning (GridSearchCV).
* **Models Compared**:
    * **Random Forest**: Achieved superior performance to identify positive cases and minimize medical risk (Screening focus).
    * **MLP (Neural Network)**: While effective, it was outperformed by the Random Forest

## How to Run the Project

1.  Clone this repository or download the files.
2.  Ensure the file **`diabetes.csv`** is present in the root directory (or update the path in the notebook if mounting Google Drive).
3.  Open the `Artificial_Intelligence_Project.ipynb` file in an environment such as Google Colab or Jupyter Notebook.
4.  Run the cells in order to reproduce the preprocessing steps, training, and evaluation graphs (ROC Curves, Confusion Matrices).

---
