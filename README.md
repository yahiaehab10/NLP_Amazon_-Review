# NLP Amazon Data

## Overview
NLP Amazon Data is a Python-based project focused on analyzing and processing Amazon product reviews. It implements various NLP techniques and machine learning models to extract insights and build sentiment classification models. The project demonstrates a complete pipeline from data loading and preprocessing to advanced model evaluation.

## Features
- **Data Preprocessing**: Prepares Amazon review data, creating features like helpfulness percentage and percentage bins.
- **Sentiment Analysis**: Implements Bag of Words and logistic regression to classify sentiment as positive or negative.
- **Automation**: Automates the NLP pipeline for text classification using reusable functions.
- **Class Imbalance Handling**: Uses oversampling techniques to balance class distributions.
- **Model Optimization**: Applies hyperparameter tuning for logistic regression models.
- **Data Visualization**: Includes heatmaps for analyzing relationships between helpfulness and scores.

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- seaborn
- sklearn
- imbalanced-learn

## Usage
1. Clone the repository.
2. Install the required libraries using pip:
   ```
   pip install pandas numpy seaborn scikit-learn imbalanced-learn
   ```
3. Run the main script to explore data preprocessing, analysis, and sentiment classification.

## Steps
1. **Data Loading**: Loads Amazon review data from a CSV file.
2. **Feature Engineering**: Creates additional features like `Helpful_Percentage` and `Percentage_Bins`.
3. **Visualization**: Displays a heatmap of helpfulness percentages against product scores.
4. **Sentiment Analysis**: Uses logistic regression and Bag of Words to classify sentiment as positive or negative.
5. **Advanced Models**: Automates NLP tasks and predicts helpfulness percentage bins using logistic regression.

## Results
- Achieved a high accuracy score for sentiment classification using logistic regression.
- Balanced dataset distributions for predicting helpfulness bins using oversampling.
- Identified key words influencing sentiment through logistic regression coefficients.

## Future Work
- Expand analysis with deep learning models.
- Include additional datasets for more generalized models.
