# Wine Quality Prediction

## Overview
This project aims to predict the quality of red wine based on various chemical properties using machine learning techniques. The dataset used is the Wine Quality dataset from the UCI Machine Learning Repository.

## Dataset
The dataset contains information about different chemical properties of red wine and their corresponding quality ratings. It consists of 1,599 samples with 12 features, including acidity, sugar, pH, and alcohol content.

- **Source:** [UCI Machine Learning Repository - Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Features
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality** (Target variable)

## Visualizations
![Distribution of wine quality ratings](https://github.com/user-attachments/assets/ec650ef9-a1b2-4405-b212-a7e7cf8d24a1)

![Scatter plot comparing actual vs. predicted quality ratings](https://github.com/user-attachments/assets/b4fd7803-e1e2-4853-a51e-c210fd1befb7)

## Conclusion
In this project, we developed a machine learning model to predict red wine quality using its chemical properties. By employing a Decision Tree Regressor, we achieved satisfactory accuracy, as indicated by the evaluation metrics. The visualizations provided insights into the relationship between actual and predicted quality ratings. Future work could explore advanced algorithms and feature selection techniques to enhance model performance, demonstrating the practical applications of machine learning in the wine industry.
---
Mean Absolute Error: 0.4625
R-squared: 0.07231130172297862

## Acknowledgments
UCI Machine Learning Repository for providing the dataset.
Scikit-learn, Pandas, Matplotlib, and Seaborn for their powerful libraries that facilitate data analysis and visualization.

## Installation
To run this project, you need to have Python installed on your machine. You can install the required libraries using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
