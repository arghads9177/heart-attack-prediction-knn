# Heart Attack Analysis and Prediction

## Overview

This data science project focuses on analyzing and predicting the likelihood of heart attacks using a dataset sourced from Kaggle. The goal is to build a model that can accurately predict the risk of a heart attack based on various health indicators and medical data.

## Dataset

The dataset includes the following features:

- **Age**: Age of the patient
- **Sex**: Sex of the patient
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **ca**: Number of major vessels (0-3)
- **cp**: Chest pain type
  - Value 1: Typical angina
  - Value 2: Atypical angina
  - Value 3: Non-anginal pain
  - Value 4: Asymptomatic
- **trtbps**: Resting blood pressure (in mm Hg)
- **chol**: Cholesterol in mg/dl fetched via BMI sensor
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **rest_ecg**: Resting electrocardiographic results
  - Value 0: Normal
  - Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalach**: Maximum heart rate achieved
- **target**: Heart attack risk indicator (0 = less chance of heart attack, 1 = more chance of heart attack)

## Objective

The goal of this project is to:

1. Understand and visualize the dataset.
2. Train a classification model to accurately predict the heart attack based on the some medical features.
3. Evaluate the performance of different classification models using metrics such as accuracy, precision, recall, and F1-score.

## Steps Involved

1. **Data Exploration**:
   - Visualize the data to understand the distribution of features.
   - Analyze the relationships between different features using scatter plots, pair plots, and correlation matrices.
   
2. **Data Preprocessing**:
   - Handle any missing values (though none are present in this dataset).
   - Split the data into training and testing sets for model evaluation.
   
3. **Model Training**:
   - Build and train classification the model using algorithms such as:
     - K Nearest Neighbors
   
4. **Model Evaluation**:
   - Evaluate the models using appropriate classification metrics:
     - **Accuracy**: Percentage of correctly classified instances.
     - **Precision**: The proportion of predicted positives that are actually positive.
     - **Recall**: The proportion of actual positives that are correctly predicted.
     - **F1-Score**: The harmonic mean of precision and recall.
     - **Confusion Matrix**: To visualize the true positives, false positives, true negatives, and false negatives.

## Model Performance Metrics

- **Accuracy**: Measures how often the classifier makes the correct predictions.
- **Precision and Recall**: Evaluate the performance when dealing with imbalanced classes (though this dataset is balanced).
- **F1-Score**: Useful when balancing precision and recall.
- **Confusion Matrix**: To visualize how well the model performed in each class.

## Visualizations

Here are some suggested visualizations to explore the Iris dataset:

1. **Scatter Plots**: Compare the distribution of features like chlestoral, blood pressure for the prediction of heart attack.
2. **Pair Plots**: Show pairwise relationships between features.
3. **Heatmaps**: Show the correlation between features.
4. **Box Plots**: Display the distribution of features.
   
## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for analysis and model training
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model development
- `models/`: Saved models and model evaluation results
- `README.md`: Project overview and documentation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/arghads9177/heart-attack-prediction-knn.git
2. Navigate to the project directory:
   ```sh
   cd heart-attack-prediction

## Usage

Explore the dataset using the provided Jupyter notebooks in the notebooks/ directory.

### Data Exploration

- This notebook includes steps for data loading, preprocessing, and initial analysis.
- This notebooks cover data preprocessing, feature engineering, model training, and evaluation.
  
## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact `Argha Dey Sarkar` at `email2argha@gmail.com`.
