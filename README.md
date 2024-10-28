## Housing Data Analysis and Price Prediction Project

In this project, I performed a comprehensive analysis of housing data, focusing on data wrangling, exploratory data analysis, feature engineering, and predictive modeling. This project included the following steps:

1. Data Cleaning and Preparation: Imported and cleaned the dataset, handling missing values by replacing them with the mean for specific columns (bedrooms, bathrooms). Removed unnecessary columns and checked for data types and distributions to ensure accuracy.

2. Exploratory Data Analysis (EDA): Conducted an analysis of the data to understand the relationships between features. Used visualizations like boxplots and regression plots to assess the correlation between variables (e.g., waterfront views and price). Calculated correlations to determine that features such as sqft_living and grade have the strongest relationship with price.

3. Model Development: Created linear regression models to predict house prices using various features.

  * Single-feature models using long and sqft_living to evaluate R² and gain initial insights.
  * Multi-feature models using a combination of features including floors, waterfront, lat, and others to enhance prediction accuracy.

4. Pipeline and Polynomial Transformation: Constructed a Pipeline object that included scaling, polynomial transformation, and linear regression to assess the impact of higher-order features on prediction accuracy. Calculated R² to measure performance.

5. Model Evaluation and Refinement:

  * Split the data into training and testing sets.
  * Implemented Ridge Regression to reduce overfitting, setting a regularization parameter of 0.1 and calculating R² on test data.
  * Performed second-order polynomial transformation on training and testing data to improve predictive power, especially with non-linear features.

Through this project, I developed proficiency in predictive modeling, using tools like scikit-learn for linear regression, polynomial features, and Ridge regression, as well as seaborn and matplotlib for visualization. This project demonstrated the impact of feature engineering and regularization techniques on predictive accuracy in housing price predictions.
