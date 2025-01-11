# Admission Classification and Menu Recommendation

## Overview

This project demonstrates the use of classification techniques for prediction and recommendation. It utilizes two datasets:
1. `Admission_Chance_Classification.csv` to predict the admission chances of students using classification models.
2. `burger-king-menu-2.csv` to recommend similar food items based on their attributes using decision trees.

The project includes the use of Decision Trees and Random Forest classifiers, as well as tree pruning techniques to improve model performance.

## Purpose

The purpose of this project is to apply classification techniques in two distinct areas:
1. **Student Admission Prediction:** Using the `Admission_Chance_Classification.csv` dataset, we aim to predict the admission status (`Admit` column) of students based on various factors using Decision Trees and Random Forest classifiers.
2. **Food Item Recommendation:** Using the `burger-king-menu-2.csv` dataset, we recommend similar food items within a specific category (e.g., Burgers, Chicken, or Breakfast) based on food attributes using Decision Trees.

## Tasks

### 1. Classification using `Admission_Chance_Classification.csv`
1. **Train-Test Split:** Split the data into a training set and test set (70% for training and 30% for testing).
2. **Decision Tree Classifier:** Build a classification model using Decision Trees to predict the admission status (`Admit` column). Visualize and interpret the decision tree, and evaluate feature importance.
3. **Tree Pruning Analysis:** Perform pruning to reduce overfitting and visualize the pruned tree.
4. **Random Forest Classifier:** Build a Random Forest classifier, compare classification accuracy with different values of `n_estimators` (10, 50, 100, 150, 200).
5. **Comparison of Models:** Compare the performance of the Decision Tree and Random Forest classifiers in terms of accuracy and other relevant metrics.

### 2. Recommendation using `burger-king-menu-2.csv`
1. **Decision Tree for Recommendations:** Build a decision tree to recommend similar food items from a chosen category (Burgers, Chicken, or Breakfast). Interpret the decision tree and provide insights into the recommendations.
   - Filter the data based on the category.
   - Remove the `Category` column and use the `Item` column as the target (`Y`).
   - Discuss the attributes that influence food recommendations.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/your-username/admission-classification-and-menu-recommendation.git
