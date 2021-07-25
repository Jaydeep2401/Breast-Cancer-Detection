## Breast Cancer Detection

This Repository contains Breast Cancer Detection model where we have classified type of tumor (Benign and Malignant) present in Breast Mass.

### Contents:

- Dataset folder containing dataset used.
        - Reference: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- Jupyter Notebook containing implementation of the project.

### Summary of Project:

- Cleaned the data and plotted beautiful visualization.
- Normalized the data to bring different features in same scale.
- Applied Principal Component Analysis (PCA) and reduced the dimensions.
- Used the obtained data to train on three different algorithms namely, Logistic Regression, Support Vector Machine (SVM) and Naive Bayes.
- Evaluated the trained models using precision, recall, f1 score and stratified k fold cross validation accuracy.
- Improved performance of models by Hyperparameter tuning using Grid Search.
- Plotted Learning curves, Box plot for comparing cross validation accuracies of different models.
- Finally used ROC curve to select the best performing model.

### Libraries used:
- Numpy
- Pandas
- Sci-kit learn
- Matplotlib
- Seaborn

### Contributors:

- [Jaydeep](https://github.com/Jaydeep2401)
- [Aynaan](https://github.com/Aynaan)