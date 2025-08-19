# Car Price Prediction Project

## Project Aim 
The goal was to predict used car prices based on various vehicle features and compare different machine learning models in terms of **prediction accuracy** and **training speed**.



*Please note that the results of each model in the summary section is reflective of the platform the project was run on during its completion. You will see different results in some of the cells due to this project being run on a different device afterwards.*
---


## Dataset
The dataset includes information about cars listed for sale, such as:
- Vehicle type
- Registration year and month
- Power (horsepower)
- Mileage
- Fuel type
- Gearbox
- Model and brand
- Price (target variable)

## Models
Four models were trained and evaluated:
1. **Linear Regression** – baseline sanity check  
2. **Decision Tree Regressor**  
3. **Random Forest Regressor**  
4. **LightGBM Regressor** – gradient boosting  

---

## Results
| Model                  | RMSE   | Training + Prediction Time |
|-------------------------|--------|----------------------------|
| Linear Regression       | ~2678  | Very fast                  |
| Decision Tree Regressor | ~2109  | ~4.4 s                     |
| Random Forest Regressor | ~1665  | ~880 s (very slow)         |
| LightGBM Regressor      | ~1636  | ~15 s                      |
  
LightGBM achieved the **best performance** (lowest RMSE) while being far more efficient than Random Forest, making it the most suitable model for this task.

---

## Tools Used
- Pandas, NumPy  
- Scikit-learn  
- LightGBM  
- Matplotlib / Seaborn (for visualization)
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction
