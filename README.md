# ML_PROJECTS REVIEW
![ml_lifecycle](https://github.com/Kaveeri16/ML_Projects/assets/139801912/75d2aa76-ea04-486f-b36d-219e6966f4c7)


Let's explore all the machine learning projects of my GitHub repository in brief.

## INDEX:

1. Air Index Quality Predictor
2. Bike Sales Analysis
3. Mobile Price Classification
4. Digital Music Store Data Analysis
5. Real Estate Price Predictor
6. Student Performance Indicator


## AIR QUALITY INDEX PREDICTION:
![AQI predict](https://github.com/Kaveeri16/ML_Projects/assets/139801912/22202172-5661-4781-bcf6-62e07c97f1cd)


#### Problem Statement and Objectives:
The project addresses the critical concern of predicting air quality index levels, which is crucial for public health and environmental monitoring. The primary objective is to develop a robust model capable of accurately forecasting air quality index values, providing valuable insights for residents and policymakers. 

#### Motivation:
The project's motivation arises from the pressing need to monitor and improve air quality for the well-being of communities. Predicting air quality index values empowers individuals and authorities to take timely actions to mitigate air pollution's adverse effects. This can help policymakers make informed decisions about air quality management.

#### Data Collection & Preprocessing:
The project showcases an impressive data collection process that includes web scraping and Beautiful Soup for data retrieval from multiple sources, , which shows their capability to handle unstructured data. We have also performed feature engineering, selection, and hyperparameter optimization, which are crucial steps in building a robust machine learning model.

#### Resource and Installation:

#### Deployment:
The deployment aspect of the project is commendable, leveraging the Heroku platform and the Flask framework for seamless accessibility. The utilization of various regression models, including Linear Regression, Lasso Regression, Decision Tree, KNN Regression, Random Forest Regression, and XGBoost Regression, reflects a commitment to model diversity and robustness. The use of AutoML further demonstrates the ability to leverage advanced machine learning tools.

#### Conclusion:
In conclusion, the "Air Quality Index Prediction" project addresses a critical environmental and public health challenge. It excels in data collection, preprocessing, and model deployment, showcasing versatility through various regression models and AutoML. The incorporation of code editors, hyperparameter tuning, ANN, and diligent model evaluation underscores a strong commitment to model performance and reliability. This project holds significant potential for improving air quality monitoring, aiding policymakers, and contributing to a healthier environment.


## 5. Real Estate Price Predictor:
![houseprice](https://github.com/Kaveeri16/ML_Projects/assets/139801912/6efe85eb-d960-4b4f-ab60-b0f732a6a8d5)



#### Problem Statements and Objectives:
The project aims to create a real estate price predictor using supervised learning techniques for Boston houses. The primary objective is to develop a reliable model that can accurately predict house prices based on various features. This model will assist prospective buyers, sellers, and real estate professionals in making informed decisions.

#### Motivation:
The motivation behind the Real Estate Price Predictor project is rooted in the need for more transparency and data-driven decision-making in the real estate market. Historically, buying or selling a house has been a complex and often opaque process, with prices influenced by various factors. Our project aims to empower individuals and professionals in the Boston real estate market with a tool that provides accurate and fair price predictions. By leveraging the power of machine learning, we seek to bridge the information gap, reduce uncertainty, and enhance the overall real estate experience for all stakeholders. This project aligns with the broader goal of using technology to make traditionally inaccessible information more accessible and usable, ultimately contributing to more informed and efficient real estate transactions.

#### Data Collection and Preprocessing:
 The project involves collecting data on Boston houses, including features such as the number of rooms, crime rate, and proximity to amenities, etc. The collected data is preprocessed to handle missing values, outliers, and feature scaling.

CRIM: per capita crime rate by town
ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: proportion of non-retail business acres per town
CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
NOX: nitric oxides concentration (parts per 10 million)
RM: average number of rooms per dwelling
AGE: proportion of owner-occupied units built prior to 1940
DIS: weighted distances to five Boston employment centres
RAD: index of accessibility to radial highways
TAX: full-value property-tax rate per $10,000
PTRATIO: pupil-teacher ratio by town
B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT: % lower status of the population
MEDV: Median value of owner-occupied homes in $1000's 

#### Deployment: 
The model is deployed using Flask, a web framework for Python. GitHub Actions is used for continuous integration and deployment. The application is hosted on Heroku and Docker containers are used for containerization. This allows users to access the predictor through a web interface.

#### Evaluation Metrics:
To assess the model's performance, we employed evaluation metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Results on validation and test datasets indicate the model's accuracy.

#### Resource Utilization:
1. Anaconda
2. Jupyter Notebook
3. Python Libraries
```pip install pandas numpy matplotlib scikit-learn tensorflow```
4. Dataset: [Link to UCI Machine Learning Repository - Boston Housing Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/)

#### Conclusion:
In conclusion, our Real Estate Price Predictor project has successfully achieved its objectives. It provides a valuable tool for those involved in the Boston real estate market, offering accurate price predictions and insights. The model's deployment through Flask, GitHub Actions, Heroku, and Docker ensures accessibility to a wide user base, while ongoing monitoring and ethical considerations reflect our commitment to its continued success.


