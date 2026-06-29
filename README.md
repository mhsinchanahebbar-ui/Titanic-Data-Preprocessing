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


## Libraries Used

- Pandas
- NumPy
- Matplotlib
