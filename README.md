# Delivery Time Prediction for E-Commerce Orders Using Machine Learning

## Machine Learning Based Logistics Prediction System

## Project Description

The Delivery Time Prediction System is a machine learning-based regression model designed to estimate the delivery time of e-commerce orders. The system analyzes various operational and environmental factors such as distance, traffic conditions, weather severity, order characteristics, and pickup time to generate accurate delivery time predictions.

The project is implemented using Python and Scikit-learn. An interactive user interface is developed using Gradio, allowing users to input order details and instantly receive a predicted delivery time.

This project demonstrates the practical application of machine learning techniques including data preprocessing, feature engineering, regression modeling, model evaluation, and deployment.

---

## Aim

To design and develop a machine learning-based system that predicts delivery time for e-commerce orders using operational and environmental factors.

---

## Working Principle

1. The user enters order and delivery-related details into the system.
2. The dataset undergoes preprocessing and feature engineering.
3. Time-based features are transformed using cyclical encoding.
4. The data is split into training and testing sets.
5. Multiple regression models are trained.
6. Models are evaluated using performance metrics.
7. The best-performing model is selected and saved.
8. The trained model generates real-time delivery time predictions through a Gradio interface.

---

## Methodology

### 1. Dataset Preparation
- Synthetic dataset generation in CSV format
- Inclusion of numerical and categorical features
- Storage and loading using Pandas

### 2. Data Preprocessing and Feature Engineering
- Handling missing values
- Encoding categorical features
- Cyclical encoding of pickup hour using:

```python
hour_sin = sin(2π × pickup_hour / 24)
hour_cos = cos(2π × pickup_hour / 24)
```
## 3. Model Training

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Model comparison using evaluation metrics  

---

## 4. Model Evaluation

- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  
- Mean Absolute Percentage Error (MAPE)  

---

## 5. Deployment

- Best model saved using Joblib  
- Gradio interface created for user interaction  
- Real-time prediction output display  

---

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Joblib  
- Gradio  

---

## Key Input Features

- Distance (km)  
- Order Size  
- Weight (kg)  
- Number of Items  
- Warehouse Processing Time  
- Courier Speed  
- Traffic Index  
- Weather Severity  
- Pickup Hour  
- Day of Week  
- Holiday Flag  
- Priority Flag  

---

## Project Screenshot
 ### User Interface 
 ![User Interface](images/Delivery_time_prediction_UI.png)

---

## Skills and Concepts Applied

- Machine Learning  
- Regression Modeling  
- Feature Engineering  
- Cyclical Encoding  
- Model Evaluation  
- Data Analysis  
- UI Development using Gradio  

---

## Applications

- E-commerce delivery estimation  
- Logistics planning  
- Supply chain optimization  
- Customer satisfaction improvement  

---

## Future Enhancements

- Integration with real-world datasets  
- Cloud deployment  
- Live traffic API integration  
- Route optimization system  
- Advanced ensemble models  

---

## Author

Damini M K  
Artificial Intelligence/Machine Learning Project    
