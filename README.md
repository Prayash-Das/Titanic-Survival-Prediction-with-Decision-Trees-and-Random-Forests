# Titanic Survival Prediction using Decision Trees and Random Forests

This repository contains code for predicting survival on the Titanic using machine learning techniques, specifically decision trees and random forests. The code is written in Python and executed in a Jupyter Notebook (Titanic_Survival_Prediction.ipynb).

## Dataset

The dataset used in this project is the famous Titanic dataset, which contains information about passengers aboard the Titanic, including features like age, sex, ticket class, siblings/spouses aboard, and whether they survived or not.

## Code Overview

1. **Data Preprocessing**: The dataset is preprocessed by removing irrelevant columns, encoding categorical variables, and splitting the data into training and testing sets.
2. **Decision Tree Classifier**: A decision tree classifier is trained on the training data and visualized using matplotlib.
3. **Hyperparameter Tuning**: GridSearchCV is used to find the best hyperparameter (max_depth) for the decision tree classifier.
4. **Pruned Decision Tree**: A pruned decision tree is built using the best hyperparameter and visualized for better understanding.
5. **Random Forest Classifier**: A random forest classifier is trained with 50 estimators and the best max_depth parameter.
6. **Model Evaluation**: The performance of the pruned decision tree and random forest classifiers is evaluated using accuracy scores and confusion matrices.

## Files in the Repository

- Titanic_Survival_Prediction.ipynb: Jupyter Notebook containing the Python code.
- README.md: This file providing an overview of the project.

## How to Use

1. Clone the repository to your local machine using git clone https://github.com/Prayash-Das/Titanic-Survival-Prediction.git.
2. Open the Jupyter Notebook Titanic_Survival_Prediction.ipynb` to view and run the code.
3. Make sure you have Python and the required libraries installed (pandas, numpy, scikit-learn, matplotlib).
4. Run each cell in the notebook to preprocess the data, train the models, and evaluate their performance.
5. Explore the visualizations of decision trees and confusion matrices to understand the model's behavior.

## Conclusion

This project demonstrates how decision trees and random forests can be used for binary classification tasks like predicting survival outcomes. It also highlights the importance of hyperparameter tuning and model evaluation in machine learning workflows.

Feel free to experiment with different hyperparameters, feature engineering techniques, or even try other classification algorithms to improve the model's performance.

**Note:** Remember to cite the source of the dataset if you use it for any research or publication. The Titanic dataset is often used for educational and learning purposes in data science and machine learning.
