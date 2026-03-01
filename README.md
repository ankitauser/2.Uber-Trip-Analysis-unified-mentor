# Uber Trip Analysis

##  Project Overview
This project analyzes Uber trip data in New York City to uncover demand patterns, identify peak travel times, and build predictive models for ride forecasting.  
Using Python, SQL, and machine learning, the analysis highlights how temporal and spatial factors influence ride demand and resource allocation.

##  Tools & Technologies
- Python (pandas, NumPy, scikit-learn, seaborn, matplotlib)
- SQL & Excel for preprocessing
- Jupyter Notebook / VS Code
- Machine Learning (XGBoost, Random Forest, Gradient Boosted Regression Trees)

##  Dataset
The dataset includes:
- **Trip Details**: Date/Time, latitude, longitude, base company code  
- **Aggregated Data**: Daily pickups across Uber and other for-hire vehicle companies  
- **Time Series Data**: Hourly resampled trip counts for forecasting  

*(Data sourced from NYC Taxi & Limousine Commission via FOIL request, also available on Kaggle)*

## Workflow
1. **Data Preprocessing**  
   - Convert Date/Time to datetime objects  
   - Extract features (hour, day, weekday, month)  
   - Handle missing values and categorical encoding  

2. **Exploratory Data Analysis (EDA)**  
   - Trips per hour and day of week  
   - Seasonal decomposition of demand trends  
   - Visualization of peak demand periods  

3. **Feature Engineering**  
   - Lagged features for time series forecasting  
   - Dummy variables for categorical bases  

4. **Model Building**  
   - Train/test split using temporal logic  
   - Models: Random Forest, XGBoost, Gradient Boosted Regression Trees  
   - Ensemble model combining predictions  

5. **Model Evaluation**  
   - Metrics: Mean Absolute Percentage Error (MAPE)  
   - Comparative analysis of models  

##  Key Insights
- **XGBoost** achieved the best performance with MAPE ~8.37%.  
- **Random Forest** and **GBRT** performed reasonably well but slightly less accurate.  
- **Ensemble model** improved stability with MAPE ~8.60%.  
- Demand shows strong seasonality and peaks during specific hours/days.  

##  Deliverables
- Jupyter Notebook with full analysis  
- Visualizations (seasonal decomposition, predictions vs actuals)  
- Trained ML models for forecasting  


   git clone https://github.com/ankitauser/Uber-Trip-Analysis.git

