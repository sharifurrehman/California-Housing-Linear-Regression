# California Housing Price Prediction

## Project Overview
This project uses Multiple Linear Regression to predict house values using the California Housing Dataset. It demonstrates how machine learning can use multiple features to estimate housing prices.

## Objectives
- Load and explore the California Housing Dataset.
- Prepare features and target variables.
- Split the data into training and testing sets.
- Train a Multiple Linear Regression model.
- Evaluate model performance using Mean Squared Error (MSE).
- Analyze feature importance and visualize predictions.

## Dataset
The dataset is provided by Scikit-learn and contains 20,640 records.

**Input Features:**
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

**Target:** `MedHouseVal` — median house value, represented in units of $100,000.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Workflow
1. Dataset loading and exploration
2. Missing-value checking
3. Feature and target separation
4. Train-test split (80% training, 20% testing)
5. Multiple Linear Regression model training
6. House value prediction
7. MSE and RMSE evaluation
8. Feature importance analysis
9. Actual vs. predicted visualization

## Model Evaluation
The model is evaluated using Mean Squared Error (MSE). A lower MSE generally indicates better predictions on the same dataset and evaluation setup.

**MSE:** Add your actual result after running the notebook.

## Key Findings
After running the notebook, record:
- The most important predictive features.
- The final MSE and RMSE values.
- What the prediction errors indicate about model performance.

