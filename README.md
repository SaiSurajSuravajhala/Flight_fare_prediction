# Flight Fare Prediction

This project aims to predict flight fares based on various factors such as departure time, airline, source and destination cities, duration, and more. 
By leveraging machine learning techniques, the model provides insights that can help airlines optimize pricing strategies and assist travelers in making cost-effective decisions.

---

## Project Overview

In this project, I developed a predictive model for flight fares using historical flight data. The key steps in the process included:

### Data Collection & Preprocessing
- **Data Cleaning:**  
  Removed or imputed missing values and outliers to ensure a robust dataset.
- **Feature Engineering:**  
  Created new features from datetime information (e.g., journey duration, departure hour), and encoded categorical variables (airlines, source, destination) using techniques like one-hot encoding.
- **Exploratory Data Analysis (EDA):**  
  Conducted visualization and statistical analysis to understand relationships between features and fare prices.

### Model Development
- **Feature Selection:**  
  Utilized correlation analysis and feature importance ranking to select the most relevant features.
- **Model Training:**  
  Experimented with several regression models including:
  - **Linear Regression**
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
- **Model Evaluation:**  
  Evaluated the models using metrics such as RMSE (Root Mean Squared Error) and R-squared to determine the best performer.
- **Hyperparameter Tuning:**  
  Fine-tuned the selected model parameters to improve prediction accuracy and generalization.

### Model Deployment & Insights
- **Final Model:**  
  The best model was selected based on validation performance and further tuned to achieve optimal results.
- **Interpretation:**  
  Model insights were generated to understand the key factors affecting flight fares, providing actionable insights for stakeholders.

---

## Dataset

The dataset comprises historical flight information including:
- **Airline:** Name of the airline operating the flight.
- **Source & Destination:** The departure and arrival cities.
- **Date and Time:** Departure date and time, which were used to extract additional temporal features.
- **Duration:** Total flight duration.
- **Stops:** Number of stops made during the flight.
- **Fare:** The target variable representing the flight fare.

Data cleaning and preprocessing steps ensured that the dataset was well-suited for predictive modeling.

---

## Why This Project is Useful

- **For Airlines:**  
  Helps in dynamic pricing and revenue management by predicting optimal fares.
- **For Travelers:**  
  Provides insights into fare trends, enabling travelers to book flights at the best prices.
- **For Researchers:**  
  Demonstrates a systematic approach to solving real-world regression problems using feature engineering, model selection, and hyperparameter tuning.

---

## Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/flight-fare-prediction.git
   cd flight-fare-prediction
   pip install -r requirements.txt

