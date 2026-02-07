# Crop Yield Prediction using Machine Learning

## Problem Statement
Build a machine learning model that predicts crop yield using a real-world agricultural dataset and explain the results clearly.

## Dataset
This project uses a real-world agricultural dataset (FAO-style data) containing information such as:
- Crop type
- Year
- Region (area)
- Yield values

The dataset does not include environmental factors like rainfall or temperature, which impacts model performance.

## Approach
The following steps were followed in this project:

1. Data loading and cleaning  
2. Filtering records related to crop yield  
3. Encoding categorical features (crop type and region)  
4. Train-test split  
5. Model training using Linear Regression  
6. Model evaluation using standard metrics  
7. Visualization of actual vs predicted values  

## Features Used
- **Year**
- **Crop type (encoded)**
- **Region / Area (encoded)**

## Model Used
- Linear Regression (scikit-learn)

This model was chosen for its simplicity and interpretability.

## Results & Evaluation
The model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Due to limited features in the dataset, the R² score is low. This highlights that crop yield prediction strongly depends on additional factors such as climate, soil conditions, and farming practices, which are not present in the dataset.

## Model Performance Visualization

![Actual vs Predicted Crop Yield](actual_vs_predicted.png)

*Figure: Scatter plot showing comparison between actual and predicted crop yield values.*

## Prediction Example
The trained model was used to predict crop yield for a future year (2026) for a selected crop category as a demonstration.

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab  

## Execution
The project was developed and executed using Google Colab.  
The complete code is provided in the Jupyter Notebook included in this repository.

## Conclusion
This project demonstrates the complete machine learning pipeline on real-world agricultural data, including data preprocessing, model training, evaluation, and interpretation of results, with a focus on understanding model limitations rather than maximizing accuracy.
