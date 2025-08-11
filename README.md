# count-prediction-with-different-ml-models

This repository explores count prediction using multiple machine learning techniques. The goal is to predict the count (cnt) of occurrences (e.g., bike rentals, events, or similar demand-based counts) based on various environmental, temporal, and categorical features.

The dataset contains timestamp-based records along with weather, temperature, humidity, wind, season, and holiday/weekend indicators.

### 📂 Project Overview
The project compares the performance of the following models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Recursive Feature Elimination (RFE) for feature selection

### The workflow includes:

Data preprocessing & cleaning

Exploratory Data Analysis (EDA)

Feature selection using RFE

Model training & hyperparameter tuning

Model evaluation & comparison

### 📊 Dataset Description
The dataset columns are:

Column	Description
timestamp	Date and time of the record
cnt	Count value to be predicted
t1	Temperature in Celsius
t2	Feels-like temperature in Celsius
hum	Humidity (%)
wind_speed	Wind speed (normalized)
weather_code	Encoded weather conditions
is_holiday	1 if holiday, else 0
is_weekend	1 if weekend, else 0
season	Encoded season indicator

Note: The dataset appears to follow an hourly time-series structure.

### ⚙️ Installation & Requirements
Clone the repository:


git clone https://github.com/karthikankam/count-prediction-with-different-ml-models.git
cd count-prediction-with-different-ml-models
Install required dependencies:


pip install -r requirements.txt

Example requirements.txt:

nginx
pandas
numpy
scikit-learn
matplotlib
seaborn
### 🚀 Usage
Run the main script to train and evaluate models:


python code.ipynb
You can modify code.ipynb to:

Change the ML model used

Tune hyperparameters

Select features using RFE

### 📈 Model Evaluation
Models are compared using:

R² Score

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Results are visualized to show how different algorithms handle the count prediction problem.

### 📌 Example Applications
This methodology can be applied to:

Bike rental demand prediction

Traffic volume estimation

Retail footfall forecasting

Event attendance prediction

### 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
