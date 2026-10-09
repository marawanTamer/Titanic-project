# Titanic Survival Prediction

## About The Project

This project uses Machine Learning to predict whether a Titanic passenger survived or not.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Model

Logistic Regression was used as the classification model.

## Data Preprocessing

The project uses:

- Median imputation for numerical features
- Most frequent imputation for categorical features
- StandardScaler for numerical features
- One-Hot Encoding for categorical features

## Hyperparameter Tuning

GridSearchCV was used to find the best value of the Logistic Regression parameter `C`.

5-Fold Cross Validation was used during Grid Search.

## Evaluation

The model was evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC

## Project Workflow

Data → Preprocessing → Train/Test Split → Pipeline → Grid Search → Cross Validation → Best Model → Prediction → Evaluation

## Conclusion

The project demonstrates a complete Machine Learning workflow from data preprocessing to model evaluation.
