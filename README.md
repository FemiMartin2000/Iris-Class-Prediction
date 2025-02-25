
# Iris Class Prediction

This repository demonstrates a machine learning project for predicting iris species using the classic Iris dataset. The notebook covers data loading, exploratory data analysis, visualization, data cleaning, train-test splitting, and evaluation of multiple classification models.

## Overview

- **Data Import:**  
  The Iris dataset is loaded from a CSV file (`iris.csv`). It contains measurements for sepallength, sepalwidth, petallength, petalwidth, and the iris class (species).

- **Data Exploration & Visualization:**  
  Basic exploratory data analysis is performed, including:
  - Displaying the first few rows of data.
  - Checking for null values and data types.
  - Grouping data by species.
  - Visualizing the distribution of features using boxplots (via Seaborn).

- **Data Cleaning:**  
  Ensures the dataset is free from missing values and provides a summary of the data types and memory usage.

- **Train-Test Splitting:**  
  The dataset is split into training and testing sets (70% training, 30% testing) using Scikit-Learn's `train_test_split`.

- **Model Evaluation:**  
  Three classification models are applied and evaluated:
  - **Support Vector Classifier (SVC)**
  - **Decision Tree Classifier**
  - **Logistic Regression**  
  All models achieved an accuracy of **98.0%** on the test set.

## Files

- **iris_class_prediction.ipynb:** The Jupyter Notebook containing the complete pipeline.
- **iris.csv:** The dataset file containing the iris data.

## Setup & Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/YourUsername/iris-class-prediction.git
   cd iris-class-prediction
   ```

2. **Install Required Packages:**

   ```bash
   pip install numpy pandas scikit-learn seaborn matplotlib
   ```

### Running the Notebook

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the `iris_class_prediction.ipynb` file.
3. Run the cells sequentially to execute the complete pipeline.


