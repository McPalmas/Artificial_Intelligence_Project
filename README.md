<div align="center">
<h1>Predicting Diabetes: Decision Tree vs MLP</h1> 
<em>This project, compares the effectiveness of two supervised machine learning models: Decision Tree and Multi-Layer Perceptron (MLP). Using the <b>Pima Indians Diabetes Dataset</b>, the two models are trained and optimized using <code>scikit-learn</code> to predict the presence of diabetes in patients. Due to the small dataset size, I employ a <b>Nested Cross-Validation strategy</b> instead of a single Train/Test split. This allows us to use the entire dataset for both tuning (via GridSearchCV) and evaluation (via cross_val_predict) without overfitting, ensuring statistically reliable metrics. Performance analysis is based on metrics such as accuracy, precision, recall, F1 score, and ROC curves, obtained through cross-validation (5-fold stratified cross-validation).</em>
</div>

---

## Repository Contents

* **`Artificial_Intelligence_Project.ipynb`**: The Google Colab notebook containing all the code for data analysis, model training, and evaluation.
* **`Artificial_Intelligence.pdf`**: The scientific report describing the project's methodology, analyses, and results.
* **`diabetes.csv`**: The dataset used for training and testing.

## How to Run the Project

1.  Make sure you have the `diabetes.csv` file in the same directory.
2.  Open the `Artificial_Intelligence_Project.ipynb` file in an environment such as Google Colab or Jupyter Notebook.
3.  Run the cells in order.
