# Smart-Car-Price-Prediction-Using-Advanced-Machine-Learning-Models


## Overview
**Smart Car Price Prediction Using Advanced Machine Learning Models** is an interactive web application that predicts the price of used cars based on various car features. This project uses machine learning algorithms like Random Forest Regressor to analyze the input data and provide an estimated price for the car.

The app is built using **Streamlit** for a user-friendly interface and **Scikit-learn** for machine learning. The user can input car features like vehicle age, mileage, engine capacity, and more, to get the car price prediction instantly.

## Features
- **Interactive UI** built with **Streamlit** to input car details and display price predictions.
- **Pre-trained Machine Learning Model** to predict car prices based on input features.
- **Dynamic Inputs** for car specifications such as vehicle age, mileage, engine capacity, transmission type, etc.
- **Price Prediction** that provides a cost estimate for the user.
- **Car Recommendations**: Get a list of recommended cars around the predicted price range.

## Key Technologies
- **Python**: Programming language
- **Streamlit**: Frontend library for building web applications
- **Pandas**: Data manipulation and cleaning
- **NumPy**: Numerical computations
- **Scikit-learn**: For model building and training
- **Joblib**: To load the pre-trained machine learning models
- **Matplotlib**: For visualization (optional if added)
- **CSV**: For car dataset

## Project Structure
```plaintext
.
├── app.py                      # Main Streamlit application file
├── RandomForestRegressor_model.pkl  # Pre-trained model file
├── columns_to_match.pkl        # Column matching for input
├── car_dataset.csv             # Dataset used for analysis
├── requirements.txt            # Python dependencies file
└── README.md                   # Project documentation

'''bash
git clone https://github.com/username/smart-car-price-prediction.git
cd smart-car-price-prediction

