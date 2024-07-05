# DataScience_Project
# Inter-Department Sports Analysis and Prediction

## Project Overview

This project analyzes participation and predicts winners in inter-department sports based on data from our university sports event. It includes data preprocessing, model development using machine learning techniques, and evaluation of predictive models.


## Features

- Data cleaning, and transformation
- Model development using Gradient Boosting Classifier
- Evaluation metrics: Accuracy, Mean Absolute Error (MAE), Mean Squared Error (MSE)
- Visualization of ROC curves

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook (for development)
- GitHub (for version control and collaboration)

## Installation

1. Clone the repository:
 git clone https://github.com/vishwagna/DataScience_Project.git
2. Install dependencies using pip:
   pip install -r requirements.txt


## Usage

To use the project:
- download dataset file named 'merged.csv' and now run data_preprocessing.ipynb for preprocessing the data.
- `data_preprocessing.ipynb` file contains methods used for preprocessing the data, data cleaning, transformation, reduction and feature engineering.
- the results of preprocessing are stored in, cleaned_data.csv, transformed_data.csv and reduced_data.csv.
- Run `data_analysis.ipynb' for performing visualization analysis on dataset.

## Data

The dataset consists of:
- Student details (name, roll number, gender)
- Participation in NSO (National Sports Organization)
- Participation in sports events across years (2022, 2023)
- Winners of sports events in 2022 and 2023

## Models Developed
  - run 'ml_models.ipynb' file to run the models.
    
### Model 1: Winner Prediction Model

- **Features Used:** NSO participation, sports event participation in 2022, 2023.
- **Evaluation Metrics:** Accuracy, Mean Absolute Error (MAE), Mean Squared Error (MSE).

### Model 2: Department Prediction Model

- **Features Used:** NSO participation, sports event participation in 2022, 2023, winners in 2022.
- **Evaluation Metrics:** Accuracy, Mean Absolute Error (MAE), Mean Squared Error (MSE).

## Results

- Model 1 achieved an accuracy of 94% on the test set.
- Model 2 achieved an accuracy of 47% on the test set.





## Acknowledgments

- Thanks to the institute for providing the data.

