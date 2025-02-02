# Heart Disease Prediction Model

This project is a machine learning-based heart disease prediction system, built using four different models: Logistic Regression, Decision Tree, Random Forest, and a Voting Classifier. It features a GUI made using Flask and uses a dataset of 3000 entries to predict whether a person has heart disease.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Overview](#model-overview)
- [Contributing](#contributing)

## Features
- Predicts the likelihood of heart disease using machine learning models.
- GUI made with Flask for easy interaction.
- Four machine learning models to compare performance: Logistic Regression, Decision Tree, Random Forest, and Voting Classifier.
- Dataset with 3000 entries for training and testing.

## Technologies Used
- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Matplotlib (optional, for visualizations)

## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/Nishit9320/Heart_Disease_Prediction_System.git
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run Flask Application
```bash
flask run
```
the application will be available at ```http://127.0.0.1:5000/```

## Usage
- Access the GUI through your browser once the Flask server is running.
- Input the patient's details, such as age, blood pressure, cholesterol levels, etc.
- Click on the "Submit" button to get the heart disease prediction.

## Model Overview
The heart disease prediction system is built using the following machine learning models:

- **Logistic Regression**: Used for binary classification problems.
- **Decision Tree**: A non-parametric supervised learning method.
- **Random Forest**: An ensemble of decision trees to improve accuracy and avoid overfitting.
- **Voting Classifier**: Combines multiple models to make a final prediction based on majority voting.

## Contibuting
Feel free to submit a pull request if you'd like to improve or add more features to this project.
