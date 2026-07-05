# Car Price Prediction 

A machine learning project that predicts the selling price of a used car based on its specifications. The model is trained on historical car data and deployed using **Streamlit**, allowing users to estimate car prices through an interactive web application.

---

## Badges

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Machine Learning Workflow](#machine-learning-workflow)
- [Installation](#installation)
- [Usage](#usage)

---

# Project Overview

Pricing a used car isn't straightforward. Several factors—including the vehicle's age, mileage, fuel type, transmission, engine specifications, ownership history, and brand—play a role in determining its value.

This project uses **Linear Regression** to learn these relationships from historical data and estimate the selling price of a used car. The trained model is integrated into a **Streamlit** web application where users can enter a car's specifications and receive an instant price prediction.

---

# Features

- Predicts used car selling prices in real time
- Interactive web application built with Streamlit
- Simple and user-friendly interface
- Dropdowns and sliders for easy input
- Data preprocessing and feature encoding
- Fast predictions using a trained Machine Learning model

---

# Dataset

The dataset contains information about used cars, including:

- Car Brand
- Manufacturing Year
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission Type
- Ownership History
- Mileage
- Engine Capacity (CC)
- Maximum Power
- Number of Seats

These features are used to train the regression model and generate price predictions.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- Jupyter Notebook

---

# Machine Learning Workflow

1. Load the dataset.
2. Clean and preprocess the data.
3. Encode categorical features.
4. Split the dataset into training and testing sets.
5. Train a Linear Regression model.
6. Save the trained model using Pickle.
7. Build an interactive Streamlit application.
8. Generate predictions based on user input.

---

# Installation

### Clone the repository

```bash
git clone https://github.com/MoazzamFarooqui/CarPredictionSystem.git
```

### Navigate to the project directory

```bash
cd CarPredictionSystem
```

### Install the required packages

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

# Usage

1. Launch the Streamlit application.
2. Select the car brand.
3. Enter the vehicle details.
4. Click **Predict**.
5. View the estimated selling price.







