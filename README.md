# Fish Weight Prediction

## Project Overview

This project predicts the weight of a fish using physical measurements and category information. A Linear Regression machine learning model is used to learn the relationship between the input features and fish weight.

The project was developed using Python in Google Colab.

## Dataset

The Fish dataset is loaded from the YBI Foundation GitHub repository.

The dataset contains 159 fish records with the following columns:

- Category
- Species
- Weight
- Height
- Width
- Length1
- Length2
- Length3

## Features Used

The following features are used to predict fish weight:

- Category
- Height
- Width
- Length1
- Length2
- Length3

### Target Variable

- Weight

The `Species` column is not used as an input feature in the model.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Model

The project uses **Linear Regression** from Scikit-learn.

The dataset is divided into training and testing sets using a 70:30 split.

- Training data: 111 records
- Testing data: 48 records
- Random state: 2529

## Model Evaluation

The model is evaluated using:

### Mean Absolute Error (MAE)

**MAE: 99.5891**

### R² Score

**R² Score: 0.8398**

The R² score indicates the proportion of variation in fish weight explained by the features used in the Linear Regression model.

## Project Workflow

1. Import the required libraries.
2. Load the Fish dataset.
3. Explore the dataset using `head()`, `info()`, and `describe()`.
4. Select the input features and target variable.
5. Split the data into training and testing sets.
6. Train the Linear Regression model.
7. Generate predictions on the test data.
8. Evaluate the model using MAE and R² score.

## How to Run

1. Open the notebook `FishWeightPrediction.ipynb`.
2. Open it using Google Colab or Jupyter Notebook.
3. Run the cells sequentially.
4. The dataset will be loaded directly from the provided GitHub URL.
5. The model will train and generate fish weight predictions.
6. The final evaluation metrics will be displayed.

## Project Structure

```text
Fish-Weight-Prediction/
│
├── FishWeightPrediction.ipynb
└── README.md
