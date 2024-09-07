
# Crop Recommendation System Using Machine Learning

This project is focused on building a machine learning-based system that recommends suitable crops to farmers based on environmental and soil parameters. The system aims to enhance agricultural productivity by optimizing crop selection through data-driven decision-making.

## Table of Contents
1. [Objective](#objective)
2. [Data Source](#data-source)
3. [Tools Used](#tools-used)
4. [Data Cleaning Process](#data-cleaning-process)
5. [Data Analysis](#data-analysis)
6. [Results](#results)
7. [Recommendations](#recommendations)
8. [Contact](#contact)

## Objective
The primary objective of this project is to:
- Compare the performance of different machine learning models in predicting the most suitable crops for specific environmental conditions.
- Provide actionable insights to help farmers select the right crops to increase yield and sustainability.

## Data Source
- The dataset consists of 2200 rows and 8 columns, including:
  - **Nutrient Levels**: Nitrogen (N), Phosphorus (P), Potassium (K).
  - **Environmental Factors**: Temperature, Humidity, pH, and Rainfall.
  - **Crop Types**: 22 different crops like rice, maize, banana, etc.
- The data is used to train models to predict the best crops based on soil and environmental features.

## Tools Used
- **Python**: The primary language for data processing and machine learning.
- **Google Colab**: Used for coding and running models in a cloud-based environment.
- **Machine Learning Models**: AdaBoost, Gradient Boosting, XGBoost, CatBoost, and LightGBM.
- **Data Visualization**: For visual analysis of variable distributions and correlations.
- **Statistical Analysis**: Descriptive statistics and correlation analysis to understand the data.

## Data Cleaning Process
- **Handling Missing Values**: Addressing missing data points to ensure clean input.
- **Outlier Detection**: Box plots used to detect and handle outliers.
- **Label Encoding**: Categorical variables (crop types) converted into numerical values.
- **Data Standardization**: Standardizing features like nitrogen, temperature, and humidity.
- **Data Splitting**: Data split into training (70%) and testing (30%) sets.

## Data Analysis
- **Descriptive Statistics**: Mean, median, and standard deviation of features.
- **Data Visualization**: Bar plots, histograms, and pie charts to represent distributions.
- **Correlation Analysis**: Scatter plots and correlation matrices to explore relationships between variables.
- **Feature Importance**: Identifying key factors that impact crop prediction using models.
- **Model Performance**: Evaluation using metrics like accuracy, precision, and recall.

## Results
- **Best Model**: CatBoost showed the highest accuracy of 98.93%.
- **Other Models**: Gradient Boosting (98.33%), XGBoost (98.18%), and LightGBM (97.57%) performed well, while AdaBoost had much lower accuracy (21.06%).
- **Feature Importance**: Nitrogen, phosphorus, potassium, temperature, and humidity were key predictors.
- **Run Time**: Each model took approximately 2-3 minutes to train and test.
- **Practical Implication**: Helps farmers in selecting the most suitable crops for specific soil conditions.

## Recommendations
- **Crop Selection**: The system recommends crops based on soil nutrients (N, P, K), temperature, humidity, and rainfall.
- **Machine Learning**: Uses models like CatBoost and XGBoost for accurate crop prediction.
- **Personalized Suggestions**: Tailored recommendations for different environmental conditions.
- **Improving Yield**: Aims to help farmers select crops that optimize yield.
- **Nitrogen Management**: Focus on nitrogen content to improve crop productivity.


## Contact
For any questions or contributions, feel free to reach out.
