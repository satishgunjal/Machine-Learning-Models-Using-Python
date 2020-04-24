# Dummy Variables and One Hot Encoding
1. Machine learning models work very well for dataset having only numbers.
2. But how do we handle text information in dataset? Simple approach is to use interger or label encoding but when categorical variables are nominal, using simple label encoding can be problematic.
3. Categorical Variables: Categorical variables are two types. Nominal and Ordinal.
4. Nominal variables dont have any numeric order/relationship between each other. e.g. male, female or e.g. read, green, blue
5. Ordinal variables have some sort of numeric order/relationship between each other. e.g. graduate, masters, phd or e.g. high, medium, low
6. Since we are dealing with Nominal categorical variables we are going to use One Hot Encoding' techinique here.
7. How One Hot Encoding Works?
   - Create separate column for each category and assign binary value 1 or 0
   - Extra variables which are created for One Hot Encoding are also called as 'Dummy Variables'

# Code
1. We will use pandas get_dummies method to create dummy variables that allows us to perform one hot encoding on given dataset.
2. Alternatively we can use sklearn.preprocessing OneHotEncoder as well to create dummy variables.
   [Notebook Reference](One_Hot_Encoding.ipynb)
