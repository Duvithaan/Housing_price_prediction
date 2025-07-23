#  Titanic Survival Prediction Model

This project builds a machine learning model to predict the survival of passengers on the Titanic using Python and Scikit-learn. It is based on the famous Titanic dataset and demonstrates data preprocessing, exploratory analysis, feature engineering, and logistic regression modeling.

##  Objective

Predict whether a passenger survived the Titanic disaster based on features like gender, passenger class, age, and port of embarkation.

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The dataset includes information about passengers such as:

- `Pclass` – Ticket class
- `Sex` – Gender
- `Age` – Age in years
- `SibSp` – Number of siblings/spouses aboard
- `Parch` – Number of parents/children aboard
- `Fare` – Passenger fare
- `Embarked` – Port of Embarkation

##  Steps Performed

1. **Data Cleaning**
   - Handled missing values
   - Encoded categorical variables (`Sex`, `Embarked`)

2. **Exploratory Data Analysis**
   - Used Seaborn plots to identify survival patterns based on features

3. **Feature Selection**
   - Selected relevant features to train the model

4. **Model Training**
   - Applied Logistic Regression from `sklearn`
   - Evaluated model using accuracy score

##  Results

- Achieved solid prediction accuracy on the test set using logistic regression.
- Visualized survival rates based on gender and class.

##  Files Included

- `titanic_survival_model.ipynb` – Jupyter notebook with full implementation
- `Titanic-Dataset.csv` – Dataset used for training and testing

## Future Work

- Try other classification models (Random Forest, XGBoost)
- Hyperparameter tuning
- Use cross-validation for more robust evaluation




