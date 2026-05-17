# Flight Price Prediction

This project is a Machine Learning project that predicts flight ticket prices using different flight details such as airline, source city, destination city, departure time, arrival time, number of stops, and flight duration.

## Project Overview

In this project, I:

* Loaded and explored the flight dataset
* Cleaned and prepared the data
* Converted categorical columns using Label Encoding
* Split the dataset into training and testing sets
* Trained a Random Forest Regressor model
* Evaluated the model using MSE and R² Score
* Compared actual and predicted flight prices
* Visualized prediction results using Matplotlib

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Machine Learning Model

The project uses the **Random Forest Regressor** algorithm to predict flight prices based on multiple travel-related features.

## Dataset

The dataset contains information about flights including:

* Airline
* Flight Number
* Source City
* Destination City
* Departure Time
* Arrival Time
* Stops
* Duration
* Ticket Price

## Results

The model was evaluated using:

* Mean Squared Error (MSE)
* R² Score

The predictions were also compared visually with actual flight prices.

## How to Run the Project

1. Clone the repository

```bash
git clone <https://github.com/TotoFromParadiso/FlightPricePrediction-Using-Python-and-Machine-Learning/tree/main>
```

2. Install the required libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

3. Run the Python file

```bash
python flightpriceprediction.py
```

## Author

Created by Sandro Makhatadze.
