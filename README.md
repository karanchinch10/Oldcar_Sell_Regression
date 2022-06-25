#  Used Cars Price Prediction
## Problem Statement
As Now a day we know many peoples are going to buy second hand car instaed of buying new one, because its is better investment option where we get almost 30-40% discount. but main question arise here is how will us know actual selling price of car base on their features or which factor matters mostt to determine selling price of car?? So in orer to solve this complex problem, I have taken this dataset from kaggle to build machine learning model which will predict the estimated price of car at which car should be sold base on features.

![Semantic description of image](used_car.jpg "Image Title")
## Content
This Dataset contains information of 5000+ old cars with different models and features like their Year, Name of the Company, KM driven, Power, Fuel Type and Location.
This Dataset contains total 12 features
- Name      
- Location  
- Year
- Kilometers_Driven
- Fuel_Type
- Transmission
- Owner_Type
- Mileage
- Engine
- Power
- Seats
- Price
## My Work
- I have made this model which will predict estimated price of old car base on thier features such as brand,KM drive,Power,Year and so on..
- I have done stepwise EDA (Exploratory Data Analysis) then visualizatiion to get some idea about important features or correlation of each feature with output which dominates more to predict price
- Then I have done Feature Engineering which inclueds features extraction & features construction based on my domian knowledge and visualization followed by label encoding 
- I have train multiples ML models on same data in order to Analysed & compare performance of differents models based of accuracy and complexity
- I have used all regression algorithms to train model and after comparing I got well accuracy by RandomForestRegressor after cross validation which was around 90%
- Finally Build web application in python using streamlit library and then deploy the model 
- Technical tools or library used --Python,numpy,pandas,sklearn,matplotllib,html,css,streamlit 
