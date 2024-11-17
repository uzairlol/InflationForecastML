# InflationForecastML
### **InflationForecastML**  

#### **Overview**  
This repository contains the code and resources for a machine learning-based inflation forecasting project, developed as part of the Inflation Prediction Competition organized by the Economic Growth and Forecasting (EGF) Lab, Institute of Business Administration, Karachi. The project leverages advanced feature engineering, hyperparameter tuning, and ensemble modeling techniques to predict inflation trends for 2024.

#### **Key Features**  
- Utilizes Random Forest and XGBoost models.  
- Implements an ensemble approach combining models via weighted averages.  
- Employs Recursive Forecasting for multi-step inflation predictions.  
- Includes thorough feature selection and engineering for optimized model performance.  

#### **Performance Metrics**  
- **Random Forest RMSE:** 0.9932  
- **XGBoost RMSE:** 1.1189  
- **Ensemble Model RMSE:** 1.0480  

#### **Data**  
- The dataset includes economic indicators up to 2023. Predictions for 2024 were made using Recursive Forecasting.  

#### **How to Use**  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/[your-username]/InflationForecastML.git  
   ```  
2. Run the notebooks in sequence for preprocessing, model training, and prediction.  

#### **Citation**  
This project was inspired by the following research paper:  
**Nawazish Mirza, Syed Kumail Abbas Rizvi, Bushra Naqvi, Muhammad Umar (2024).** *Inflation prediction in emerging economies: Machine learning and FX reserves integration for enhanced forecasting.* International Review of Financial Analysis, Volume 94, Article 103238. [https://doi.org/10.1016/j.irfa.2024.103238](https://doi.org/10.1016/j.irfa.2024.103238)  
