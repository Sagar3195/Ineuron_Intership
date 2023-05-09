

# Flight Fare Prediction

### Problem Statement:- 
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options. The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planning the trip will surely help many people save money and time.

### Goal:- 
The main goal is to predict the fares of the flights based on different factors available in the provided dataset.

### Approach:- 
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.

### Dataset:-
https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh

## Project Various Steps:-
### Data Exploration - 
I started exploring datasets using pandas, numpy, matplootlib and seaborn.

### Data Visualization - 
Ploted colleration matrix to get insights about dependend and independed variables. Made chats like Bocxplot,pairplot.

### Model Selection - 
Here selected best model RandomForestRegressor.

### Hyperparameter Optimization - 
Using RandomizedSearch CV to select the best parameter for training the model.

### Model Dump
As per selected trained model is dumped to pickled format for app development.

### IDE Used -
Visual Studio Code 

### Model Accuracy - 
81.3%

### Deployment - 
The project is deployed on local machine 127.0.0.1:5000/predict and AWS EC2 instance.

### Demo Video Link - [project demo video link](https://youtu.be/SqDMnFwF_mA)
### Deployment Link - 
http://ec2-16-16-146-17.eu-north-1.compute.amazonaws.com:8080/predict

