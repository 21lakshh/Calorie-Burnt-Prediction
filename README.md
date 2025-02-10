# Calories Burnt Prediction

## Project Overview
This project aims to predict the number of calories burnt during exercise based on several features such as age, gender, height, weight, and exercise data. We used data preprocessing, exploratory data analysis, and machine learning models to develop the prediction system. The final model achieved good accuracy, with the mean absolute error (MAE) as the evaluation metric.

---

## Dataset
The dataset consists of two separate data frames:
1. `exercise`: Contains data on exercises performed by individuals.
2. `calories`: Contains data on calories burnt.

### Merging the Data
The two data frames were combined into one based on a common identifier to facilitate analysis and model building.

---
## Features  
The dataset includes property attributes such as:  

- User_ID	
- Gender 
- Age 
- Height 
- Weight 
- Duration 
- Heart_Rate 
- Body_Temp 

---

## Data Preprocessing
The following preprocessing steps were performed:
- Checked for missing values and handled them (if any were found).
- Combined the `exercise` and `calories` data frames into a single data frame.
- Checked data distributions for numerical features.
- Converted categorical data into numerical values (e.g., gender).

## Exploratory Data Analysis
Key insights obtained from the data analysis:
- **Male-Female Distribution**: A pie chart was created to analyze the gender distribution.
- **Age Distribution**: Observed that younger people frequent the gym more often than older individuals.
- **Height and Weight Distribution**: Plotted distributions to understand the spread of these features.
- **Correlation Matrix**: Checked for correlations between features to identify significant relationships.

### Visualizations
- **Pie Charts**: Gender and age distributions.
- **Histograms**: Height and weight distributions.
- **Heatmap**: Correlation matrix to visualize relationships between features.

## Model Selection
We used the `XGBRegressor` model for prediction. The dataset was split into training, testing, and validation sets.

## Model Performance
The model was evaluated using the **Mean Absolute Error (MAE)** metric:
- **Training Set MAE**: 0.87
- **Testing Set MAE**: 1.56
- **Validation Set MAE**: 1.58

## Requirements
To run this project, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

---

**Feel free to contribute or provide feedback!**

