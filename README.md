![Screenshot 2025-03-08 202741](https://github.com/user-attachments/assets/b938bc04-7054-4fa3-87cd-fe1b714699eb)

# crop_yield_prediction_data_analysis_and_ML
This is the project about crop yield prediction of better harvestment by using the tools of python in data analysis and ml

### **Basic Information About the Crop Yield Prediction Project**

**Objective:**  
The aim of this project is to predict crop yield using machine learning models based on agricultural data.

**Dataset Information:**  
- The dataset contains various agricultural factors affecting crop yield.
- Features include:
  - **Rainfall (mm)**
  - **Temperature (°C)**
  - **Fertilizer (kg)**
  - **Nitrogen (N)**
  - **Phosphorus (P)**
  - **Potassium (K)**
  - **Yield (Q/acres) (Target Variable)**

**Data Preprocessing:**  
- Handled missing values by replacing them with the median.
- Removed invalid values (e.g., incorrect temperature values like ":").
- Converted data types to appropriate formats.

**Exploratory Data Analysis (EDA):**  
- Identified two distinct clusters in rainfall, temperature, and yield, indicating two different crops.
- Temperature and rainfall have the highest influence on yield.
- Macro-nutrients (NPK) have lesser importance compared to temperature and rainfall.

**Machine Learning Models Used:**  
1. **Decision Tree Regressor**
2. **Random Forest Regressor**  

- **Hyperparameter tuning** was performed using GridSearchCV.
- **Random Forest Regressor performed better** with an R² score of **0.802**, while Decision Tree Regressor had an R² score of **0.770**.

**Findings & Conclusion:**  
- **Temperature** and **Rainfall** are the most significant features in predicting crop yield.
- The dataset contains **two different crops**, affecting the yield differently.
- **Random Forest Regressor** was the best-performing model for yield prediction.

