# Flight Price Prediction

This project focuses on predicting flight ticket prices using various machine learning models. It explores data preprocessing, feature engineering, and model building to create a reliable flight price prediction system based on attributes like airline, departure time, arrival time, duration, and more.

## Project Overview

The objective of this project is to build a machine learning model that can accurately predict the price of a flight ticket based on multiple factors. By analyzing and training models on historical flight data, this project provides insights into how different factors influence flight prices.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)


## Dataset

The dataset used for this project is available on Kaggle. You can download it [here](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh).

To use this dataset:
1. Download the dataset file from Kaggle.
2. Place the file in the project directory or the specified data directory before running the notebook or Flask app.

## Features

- **Airline**: The airline operating the flight.
- **Date of Journey**: Date when the journey is scheduled.
- **Source and Destination**: The start and end points of the journey.
- **Route**: The route taken for the flight.
- **Departure and Arrival Time**: Time of departure and arrival.
- **Duration**: Duration of the flight.
- **Additional Info**: Other relevant details about the flight.

## Data Preprocessing

To prepare the data for modeling, several preprocessing steps were taken, including:

1. Converting categorical data to numerical using techniques such as one-hot encoding.
2. Handling missing values and ensuring data consistency.
3. Feature engineering to extract meaningful insights from date and time features.

## Exploratory Data Analysis

This phase included visualizations to understand the influence of various features on flight prices. Key visualizations included:

- Price distribution for different airlines.
- Impact of departure and arrival times on ticket prices.
- Relationship between flight duration and price.

## Modeling

Experimented with several machine learning models, including:

- **Decision Tree Regressor**
- **Random Forest Regressor**

Models were evaluated using performance metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), or R-squared (R²)  to assess prediction accuracy.

## Results

- The **Random Forest Regressor** demonstrated the best performance with the lowest MAE, making it the most reliable model for this dataset.
- Feature importance analysis showed that airline, duration, and journey date are significant factors influencing ticket prices.

## Installation and Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/nisch-mhrzn/Flight-Price-Prediction.git
    cd Flight-Price-Prediction
    ```

2. **Set up a virtual environment**:
    ```bash
    python -m venv env
    ```

3. **Activate the virtual environment**:
   - On Windows:
     ```bash
     env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the Flask app**:
    ```bash
    python main.py
    ```

6. **Run the Jupyter Notebook**:
   Launch the notebook to explore the code and experiment with models.
   ```bash
   jupyter notebook flight_price.ipynb
   ```

## Contributing

Contributions are welcome! Feel free to submit issues, fork the repository, and open pull requests.



--- 

