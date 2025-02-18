# Milano Housing Price Estimator

This project explores the application of linear regression to predict house prices in Milan, Italy, based on various features commonly used in real estate analysis. For this project, I created a case study in which the client is a real estate agency that requires a price prediction model for daily use. The linear regression model incorporates essential property attributes such as the number of rooms, square meters, bathrooms, price, and neighborhood, providing a comprehensive view of the factors influencing property values.

The Jupyter Notebook is available for download. Hint: For better navigation in the Jupyter Notebook, I suggest clicking on View → Table of Contents. This will display the contents in a left-side panel, making it easier to access specific sections given the length of the project, rather than scrolling down. 

## Summary of the contents:

1. Introduction to the project and sources
   
2. Case Study  
3. Introduction to the Data  
4. Import of the necessary libraries for the project  
5. Importing the data  
6. Data Cleaning  
   - Techniques used: dropping irrelevant columns, deleting NaN values, feature engineering, outliers removal based on relevant business information given by the stakeholder, outlier removal using mean and standard deviation, one-hot encoding  
7. Linear Regression model  
   - Creation of dependent variable and independent variables  
   - Creation of training sets and testing sets  
   - Calculation of R² score and of Cross-Validation to measure the accuracy of the prediction model  
   - Testing the model by inserting neighborhood and other house features to obtain the estimated price  
8. Conclusion  
