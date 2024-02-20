# Black Friday Dataset - EDA and Feature Engineering

Welcome to the Black Friday Dataset EDA and Feature Engineering repository! This project focuses on in-depth Exploratory Data Analysis (EDA) and Feature Engineering to gain insights and prepare the data for further analysis or machine learning models. The dataset used in this project consists of two CSV files: `BlackFriday_train.csv` for training and `BlackFriday_test.csv` for testing.

## Dataset Fields

### Training Data (`BlackFriday_train.csv`):
- **User_ID:** Unique identifier for each user.
- **Product_ID:** Unique identifier for each product.
- **Gender:** Gender of the user.
- **Age:** Age group of the user.
- **Occupation:** Occupation code of the user.
- **City_Category:** Category of the city where the user resides.
- **Stay_In_Current_City_Years:** Number of years the user has stayed in the current city.
- **Marital_Status:** Marital status of the user (1 for married, 0 for unmarried).
- **Product_Category_1, Product_Category_2, Product_Category_3:** Categories of the purchased products.
- **Purchase:** Purchase amount in dollars.

### Test Data (`BlackFriday_test.csv`):
- **User_ID:** Unique identifier for each user.
- **Product_ID:** Unique identifier for each product.
- **Gender:** Gender of the user.
- **Age:** Age group of the user.
- **Occupation:** Occupation code of the user.
- **City_Category:** Category of the city where the user resides.
- **Stay_In_Current_City_Years:** Number of years the user has stayed in the current city.
- **Marital_Status:** Marital status of the user (1 for married, 0 for unmarried).
- **Product_Category_1, Product_Category_2, Product_Category_3:** Categories of the products.

## Exploratory Data Analysis (EDA)

1. **Data Summary:**
   - Overview of dataset statistics, such as mean, median, and standard deviation.
   - Identify missing values, outliers, and any anomalies in the data.

2. **Univariate Analysis:**
   - Distribution analysis for each variable.
   - Visualizations, histograms, and kernel density plots for continuous variables.
   - Bar charts and pie charts for categorical variables.

3. **Bivariate Analysis:**
   - Explore relationships between variables.
   - Correlation analysis to identify patterns and dependencies.
   - Pair plots for visualizing relationships between pairs of variables.

4. **Categorical Variable Analysis:**
   - Analyze the distribution of categories within each categorical variable.
   - Use count plots and bar charts to visualize the frequency of each category.

5. **Numeric Variable Analysis:**
   - Distribution analysis of numeric variables.
   - Box plots for visualizing the spread of data.

## Feature Engineering

1. **Handle Missing Values:**
   - Impute or remove missing values based on the nature of the data.

2. **Encode Categorical Variables:**
   - Convert categorical variables into numerical representations using techniques like one-hot encoding.

3. **Age and Stay_In_Current_City_Years Transformation:**
   - Convert age groups and stay-in-city years into numerical format for better model compatibility.

4. **Create New Features:**
   - Introduce new features that might capture valuable information.
   - For example, calculate the total purchase amount per user or per product.

5. **Product_Category Features:**
   - Explore ways to use information from multiple product category fields.
   - Combine or transform these fields to create more meaningful features.

6. **Normalize or Scale:**
   - Normalize or scale numerical features if necessary.