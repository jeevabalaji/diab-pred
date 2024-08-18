# Diabetes Prediction with Machine Learning

This project aims to predict whether a person has diabetes based on specific diagnostic measurements. The prediction is made using a Machine Learning model trained on a dataset containing health-related metrics.

## Dataset

The dataset used for this project is in CSV format and contains the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1) where 1 denotes diabetes and 0 denotes no diabetes

## Project Structure

- `diabetes.csv`: The dataset used for training and testing the model.
- `diabetes_prediction.py`: The Python script that loads the data, trains the model, and evaluates its performance.
- `README.md`: This file, providing an overview of the project.

## Setup Instructions

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/jeevabalaji/diabetes-prediction.git
cd diabetes-prediction
