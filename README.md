# Iris Flower Classification Project

The Iris dataset is one of the most famous datasets in machine learning. In this project, we build and evaluate classification models to predict the species of an iris flower based on its sepal and petal measurements.

## Project Goals

- Explore the Iris dataset with descriptive statistics and visualizations
- Build and evaluate machine learning models (Logistic Regression, Random Forest, SVM)
- Apply hyperparameter tuning using GridSearchCV
- Visualize model performance and feature importances

---

## Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris)
- **Samples**: 150
- **Features**:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- **Target Classes**:
  - *Iris-setosa*
  - *Iris-versicolor*
  - *Iris-virginica*

---

## Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

---

## Techniques and Tools

- **Python Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`
- **Model Evaluation**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- **Tuning**: GridSearchCV, RandomizedSearchCV
- **Feature Importance**: Barplots using Seaborn to show the most important features from Random Forest

---

## Results

- **Best Model**: Random Forest (after tuning)
- **Accuracy**: ~97% on test data
- **Key Finding**: Petal length and width are the most discriminative features for classifying iris species.

---

## Visualizations

- Pairplots and boxplots for feature distribution
- Heatmap of feature correlation
- Bar plot of feature importances
- Confusion matrix of model predictions

---
Author: Janhavi Tamhankar  
[Linkedin](https://www.linkedin.com/in/janhavitamhankar/)
