# Car Price Prediction using Machine Learning

A machine learning project that predicts the selling price of a used car based on its specifications. The model is trained on historical car data and deployed through a simple Streamlit web application, allowing users to enter vehicle details and receive an estimated market price instantly.

---

## Project Overview

Buying or selling a used car often depends on several factors such as the brand, manufacturing year, fuel type, engine size, mileage, transmission, ownership history, and kilometers driven. Estimating a fair price manually can be difficult, so this project uses Machine Learning to make that process easier.

The application takes user input, processes it in the same way as the training data, and predicts the expected selling price using a trained regression model.

---

## Features

* Predicts used car prices in real time
* Interactive web interface built with Streamlit
* Trained on real-world car listing data
* User-friendly input controls such as sliders and dropdown menus
* Fast prediction with a pre-trained machine learning model

---

## Dataset

The project uses a dataset containing information about used cars, including:

* Car Brand
* Manufacturing Year
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Ownership History
* Mileage
* Engine Capacity
* Maximum Power
* Number of Seats

These features are used to train the model and generate predictions.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

---

## Machine Learning Workflow

1. Load and clean the dataset.
2. Perform preprocessing and encode categorical features.
3. Split the dataset into training and testing sets.
4. Train a Linear Regression model.
5. Save the trained model using Pickle.
6. Deploy the model with a Streamlit interface.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/car-price-prediction.git
```

Move into the project folder:

```bash
cd car-price-prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## How It Works

1. Select the car brand.
2. Enter the vehicle specifications.
3. Click **Predict**.
4. The model estimates the expected selling price of the vehicle.

---

