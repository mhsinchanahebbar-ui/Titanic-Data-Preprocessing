# Titanic-Data-Preprocessing
Data cleaning and preprocessing of the Titanic dataset using Python and Google Colab.
## Dataset
- Dataset: Titanic Dataset
- Rows: 891
- Columns: 12

## Steps Performed

1. Loaded the dataset using Pandas.
2. Explored the dataset structure and statistics.
3. Identified missing values.
4. Filled missing values:
   - Age → Median
   - Embarked → Mode
5. Removed Cabin column due to excessive missing values.
6. Removed unnecessary columns:
   - PassengerId
   - Name
   - Ticket
7. Encoded categorical variables:
   - Sex
   - Embarked
8. Detected outliers using boxplots.
9. Performed feature scaling using StandardScaler.
10. Split data into training and testing sets.


Task 2: Exploratory Data Analysis (EDA)

11.Steps Performed

   -Generated summary statistics such as mean, median, standard deviation, minimum, and maximum values.
   
   -Analyzed missing values and data distribution.
   
   -Created histograms for numerical features.
   
   -Created boxplots to identify outliers.
   
   -Built a correlation matrix to study relationships between features.
   
   -Examined survival patterns based on passenger characteristics.

12.Key Observations

   -Most passengers were between 20 and 40 years of age.
   
   -The Fare feature contains several high-value outliers.
   
   -Passenger Class (Pclass) has a strong influence on survival.
   
   -Passengers who paid higher fares generally had better survival rates.
   
   -Age, Fare, and Passenger Class appear to be important features for predicting survival.


# Task 3: Linear Regression

## Objective
The objective of this task was to implement and understand Linear Regression using Scikit-learn.

## Steps Performed

1. Loaded the Titanic dataset using Pandas.
2. Handled missing values in Age and Embarked columns.
3. Encoded categorical variables such as Sex and Embarked.
4. Selected relevant features for prediction.
5. Split the dataset into training and testing sets.
6. Trained a Linear Regression model using Scikit-learn.
7. Predicted fare values on the test dataset.
8. Evaluated model performance using MAE, MSE, and R² Score.
9. Visualized actual and predicted values using a scatter plot.
10. Interpreted feature coefficients to understand their impact on fare prediction.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score


