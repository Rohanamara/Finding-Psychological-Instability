# Finding Psychological Instability Using Machine Learning

This repository contains files and resources for a project aimed at identifying psychological instability using machine learning models. The primary objective is to predict mental health disorders based on patient data collected through questionnaires and analyzed using various machine learning techniques.

## Project Structure

### Files
1. **Dataset-Mental-Disorders.csv**
   - This file contains the dataset used in the project.
   - **Description**: The dataset includes patient data collected via questionnaires. It consists of features that provide insights into emotional and mental health for predicting psychological instability.
   - **Usage**: Used for training and testing machine learning models.

2. **finding-psychological-instability.ipynb**
   - This is the Jupyter notebook used for analyzing the dataset and implementing the machine learning models.
   - **Contents**:
     - Data preprocessing and cleaning.
     - Exploratory data analysis (EDA) to uncover patterns and insights.
     - Machine learning model implementation and evaluation.
     - Visualization of results.

### Dependencies
The project requires the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `TextBlob`

Make sure to install the required libraries before running the notebook:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn textblob
```

## Methodology
1. **Data Collection**: 
   - Patient responses were collected through a structured questionnaire targeting emotional and mental health indicators.

2. **Data Processing**:
   - Cleaned and transformed data to ensure compatibility with machine learning models.
   - Sentiment analysis performed using TextBlob to classify sentiments as positive, negative, or neutral.

3. **Machine Learning**:
   - Logistic regression was the primary model for its interpretability and efficiency with large datasets.
   - Accuracy and feature importance were evaluated to ensure reliable predictions.

4. **Visualization**:
   - Used graphs and charts to illustrate findings and model performance.

## How to Use
1. Clone the repository.
2. Ensure the required Python libraries are installed.
3. Place the dataset (`Dataset-Mental-Disorders.csv`) in the same directory as the notebook.
4. Open and run the Jupyter notebook `finding-psychological-instability.ipynb`.

## Results
- Logistic regression provided the best accuracy in predicting psychological instability.
- Features with the most significant impact on mental health were identified through coefficient analysis.

## Future Work
- Expand the dataset for greater generalizability.
- Explore additional machine learning models to improve accuracy.
- Investigate correlations with external factors like socioeconomic status or environment.
