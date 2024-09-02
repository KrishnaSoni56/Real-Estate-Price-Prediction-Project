# Real-Estate-Price-Prediction-Project

# Project Overview :
This project aims to predict Real Estate Prices in Bengaluru city. The prediction model is based on a dataset obtained from Kaggle, containing various features related to the location, size, number of bedrooms, and amenities of properties.

# Dataset :
The dataset used for this project was sourced from Kaggle and includes detailed information on properties across Bengaluru. Key features include:

> Location: The Area where the property is located.
> Size: The total area of the property in square feet.
> Bedrooms: Number of bedrooms in the property.
> Bathrooms: Number of bathrooms in the property.
> Price: The price of the property (target variable).

# Technology and Tools :
> Python
> Numpy and Pandas for data cleaning 
> Matplotlib for data visualization
> sklearn for Machine Learning Model Building
> Jupyter Notebook , Pycharm as IDE
> Python Flask for http server

# Data Cleaning and Feature Engineering :
To prepare the data for modeling, extensive data cleaning and feature engineering were performed:

> Handling Missing Values: Missing values were identified and appropriately handled, either through imputation or removal.
> Outlier Detection: Outliers in the dataset were detected and removed to prevent skewing the model.
> Feature Engineering: Additional features were engineered, such as converting categorical variables into numerical ones using one-hot encoding and creating new variables that capture important aspects like price per square foot.

# Data Visualization :
To gain insights into the dataset, various visualizations were created using matplotlib :

> Price Distribution: Analysis of price distribution across 2BHK and 3 BHK homes.
> Scatter Plot : Done analysis of house prices with respect to different locations.
> Histograms: Visualized hist plots for finding the critical values present in features like in bathroom feature.

# Model Development :
Multiple machine learning models were developed and tested to find the best predictor:

> Linear Regression: A simple baseline model to understand linear relationships.
> Lasso Regression: To introduce regularization and reduce the likelihood of overfitting.
> Decision Trees: To capture non-linear relationships in the data.

# After evaluating each model using cross-validation and performance metrics like RMSE, the best-performing model was selected.

# Model Deployment
The final model was saved as a Pickle file and deployed using a Flask server to provide real-time predictions. The Flask app takes user input for property details and returns the predicted price.





