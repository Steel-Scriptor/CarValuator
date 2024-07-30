# CarValuator - Car Price Predictor

Made by Steel-Scriptor (Vidit Saini) {Handled ML PART} & pandey9919 (Vijendra Pandey) {HANDLED THE WEB DEVLOPMENT AND DEPLOYMENT PART}

<img src="https://github.com/Steel-Scriptor/CarValuator/blob/main/Proj_Sample.png">

# Aim

This Project aims to build a model that predicts the price of a car based on various features such as brand
value, making, model, year, mileage, kilometers driven, age of vehicle as well as some other relevant attributes. 
It leverages machine learning techniques to provide accurate price estimations, which can be useful for buyers and sellers in
the automotive market.

Clone the Repository, Run the "application.py" file, and you then you can start using the project.

# About

## What does this project do?

1. This project takes into account brand value, model, year, fuel type, kilometers driven, and age of vehicle.
2. It then predicts the possible price of the car. For example, After Running the application file the predicted price of our Hyundai Grand i10 would be shown as 388028.64



## How does this project achieve this?

1. First of all the data was taken from Quikr.com (https://quikr.com) as they have an account of many 2nd Hand Vehicles and their Major Details.

Link for the data (uncleaned): https://github.com/Steel-Scriptor/CarValuator/blob/main/quikr_car.csv

2. As we checked the Data, Column by column, we realized that it had to be cleaned for proper Working of the Project

3. Then a Linear Regression Model was built on top of it using the cleaned data as the source.

Link for the notebook: https://github.com/Steel-Scriptor/CarValuator/blob/main/Quikr%20Analysis.ipynb

4. Then, Using Some Technologies like Flask (for creating a web interface) {WE WERE NEW TO USING THIS, SO TOOK HELP FROM A SENIOR AND INTERNET }, and HTML/CSS/JavaScript, this project was given the form of a website where we used the Linear Regression model to perform predictions.

5. AS WE LACKED TIME, THIS PROJECT MAY HAVE SOME ERRORS THAT COULD BE OVERSAWN BY US.

SO THIS PROJECT COULD BE FURTHER OPTIMIZED BY USING SOME ADDITIONAL LIBRARIES LIKE TensorFlow OR Matplotlib etc.

