
# Red Wine Quality Analysis



## Overview

This project is a data analysis and machine learning project that focuses on analyzing the quality of red wine based on various physicochemical properties. The dataset used in this analysis contains information about different attributes of red wine, such as acidity, residual sugar, alcohol content, and more. The goal of this project is to build machine learning models that can predict the quality of wine and gain insights into which factors contribute most to the perceived quality.

## Dataset

The dataset used in this project is publicly available from the UCI Machine Learning Repository. It contains 1,599 samples of red wine with 11 physicochemical properties and a quality score ranging from 3 to 8.

The features in the dataset include:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- quality
  
The target variable is the quality score, which is an integer value between 3 and 8, with higher values indicating better wine quality.

## Project Structure

The project is organized into the following main parts:

1. **Data Loading and Exploration**: In this part, we load the red wine dataset and perform an initial exploration of the data. We visualize the distribution of wine quality, check for any missing values, and identify any potential relationships between variables.

2. **Data Preprocessing**: We preprocess the data by handling missing values and encoding the quality score into binary classes (good or bad) for classification.

3. **Data Visualization**: We create various visualizations, such as histograms, boxplots, and pairplots, to gain insights into the relationships between features and their impact on wine quality.

4. **Model Building**: We train two machine learning models for wine quality prediction: Random Forest and Decision Tree classifiers. These models will be evaluated and compared in terms of accuracy and other performance metrics.

5. **Model Evaluation**: We evaluate the trained models on a separate test dataset and analyze their performance using accuracy, confusion matrix, and classification reports.

## Dependencies

The project is implemented using Python and relies on the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Clone this repository to your local machine.
2. Install the required libraries mentioned in the `Dependencies` section using `pip`.
3. Place the red wine dataset (CSV file) in the appropriate directory.
4. Open the Jupyter Notebook file `red_wine_quality_analysis.ipynb` and run each cell sequentially.

## Conclusion

Through this project, we aim to provide insights into the quality of red wine based on various physicochemical attributes. By using machine learning models, we can predict the quality of wine and understand which factors contribute most to the perceived quality. The results were remarkable, with the Random Forest Classifier exhibiting outstanding performance, achieving an accuracy of over 99%. This model demonstrated its robustness in handling complex relationships among the input features, thereby providing highly accurate predictions.
On the other hand, the Decision Tree Classifier yielded a comparatively lower accuracy of around 60%. This discrepancy in performance can be attributed to its simpler structure and potential overfitting to the training data, limiting its ability to generalize well to new instances. 
The project can be extended to include more advanced models, hyperparameter tuning, and exploring additional datasets for a more comprehensive analysis.
I hope this analysis will be beneficial for wine enthusiasts, winemakers, and anyone interested in understanding the factors that influence red wine quality.

