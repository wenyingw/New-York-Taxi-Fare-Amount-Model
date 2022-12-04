# New York Taxi Fare Amount Model 

### Overview:
The main objective of this project is to analyse the total fare amount in New York City Taxi based on data collected by The New York City Taxi and Limousine Commission (TLC). The project focuses on analysing the data from January 2019 to July 2021 using Spark. This report will present the process of loading, transforming and analysing data. Furthermore, the selection from multiple machine learning models is made for predicting a total amount of a trip.

A few models were compared to select the best fit. As it is a regression question, four types of models included in SparkML are considered to train the model, including Random Forest Regression Model, Linear Regression Model, Generalized Linear Regression Model, and Gradient Boosted Tree Regression Model. Considering the relatively limited native feature selection functions in Pyspark's MLlib.

### Output:
- [Written Report](https://github.com/wenyingw/New-York-Taxi-Fare-Amount-Model/blob/main/report_new_york_taxi_fare_amount_model.pdf)

- [Workfile](https://github.com/wenyingw/New-York-Taxi-Fare-Amount-Model/blob/main/workfile_new_york_taxi_fare_amount_model%20.ipynb)

### Result:
Models selected to be trained on the whole dataset are Linear Regression Model and Generalized Linear Regression Model based on their performance from the two experiments. And Generalized Linear Regression Model has better performance with a lower RMSE score. Moreover, the RMSE for predicted test data is about **0.8254** by **Generalized Linear Regression Model**, which is even better than the score on the validation set. This might be due to the size of the test dataset being very small compared to train and validation sets.

<sub><sup>Edit on Apr 26, 2020</sup></sub>