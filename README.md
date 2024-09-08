# House Price Prediction in Jabodetabek

The repository contains machine learning process to predict house price in Jabodetabek based on tehir inputs using multiple machine learning model such as Linear Regression, Lasso, Random Forest, SVR and XGBoost.

The model has been trained using input and output data sourced from Kaggle (https://www.kaggle.com/datasets/nafisbarizki/daftar-harga-rumah-jabodetabek/data). Below is a description of each input and output feature used in this model:

Input (26 features)
url : (obj) The URL of the house listing
title : (obj) The name of the house
address : (obj) The address of the house
district : (obj) The district where the house is located
city : (obj) The city where the house is located
lat : (float) The longitude coordinate of the house
long : (float) The latitude coordinate of the house
facilities : (obj) The facilities provided by the house
property_type : (obj) The type of property
ads_id : (float) ads id to identify the house
bedrooms : (float) The number of bedrooms
bathrooms : (float) The number of bathrooms
land_size_m2 : (float) The land size in square meters (m²)
building_size_m2 : (float) The building size in square meters (m²)
carports : (float) The number of carports
certificate: (obj) The type of legal certificate
electricity: (float) The electrical capacity
maid_bedrooms: (float) The number of bedrooms for housemaids
maid_bathrooms: (float) The number of bathrooms for housemaids
floors: (float) he number of floors
building_age: (float) The age of the building (in years)
year_built: (float) The year the building was constructed
property_condition: (obj) The physical condition of the house
building_orientation: (obj) The orientation of the building
garages: (float) The number of garages
furnishing: (obj) The furnishing status of the house

2. Output

price_in_rp : (float) The estimated price of the property in Rupiah

To predict house prices in Jabodetabek using machine learning models, we will use Linear Regression, Lasso, Random Forest, SVR and XGBoost.

# Conclution
The analysis reveals that XGBoost is the best-performing model based on valid_score, with a lower RMSE compared to other models. Random Forest also performs well but has a slightly higher valid_score compared to XGBoost. However, both models show significant difference between valid_score and train_score, indicating potential overfitting. For future work, it is suggested that further hyperparameter tuning is needed to enhance model performance.
