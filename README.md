# ozone-AQI-prediction

# AQI Prediction Using Machine Learning

This project aims to predict the Air Quality Index (AQI) using various machine learning classification models. It provides an end-to-end workflow for training, testing, and evaluating multiple classifiers, helping to identify the best-performing model for AQI prediction.

## Models Implemented

- **Logistic Regression**
- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN) Classifier**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **Gradient Boosting Classifier**

## Project Structure

The Jupyter Notebook includes the following steps:

1. **Data Loading & Preprocessing**  
   - Load the AQI dataset.
   - Handle missing values, outliers, and categorical variables if needed.

2. **Feature Selection & Engineering**  
   - Select relevant features for training the models.

3. **Model Training & Evaluation**  
   - Train each model on the dataset.
   - Evaluate models using appropriate metrics (accuracy, precision, recall, F1-score).

4. **Model Comparison**  
   - Compare the performance of different models and choose the best one.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

### Installation

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/aqi-prediction.git
cd aqi-prediction
pip install -r requirements.txt
