
---

## 📊 Workflow  

### 1. Import Libraries  
- pandas, numpy  
- matplotlib, seaborn  
- sklearn  
- xgboost, lightgbm  

---

### 2. Data Loading  
- Multiple datasets are loaded and merged  
- Includes theater information and audience data  

---

### 3. Exploratory Data Analysis  
- Missing value analysis  
- Distribution of audience count  
- Day-of-week trends  
- Time-series visualization  

---

### 4. Data Preprocessing  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Merging datasets  

---

### 5. Feature Engineering  

- Day-of-week encoding  
- Lag Features (1, 7, 14, 30 days)  
- Rolling Mean (7, 14, 30 days)  
- Theater-level aggregations  

---

### 6. Model Training  

Models used:
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost  
- LightGBM  

Metrics:
- RMSE  
- MAE  
- R² Score  

---

### 7. Model Selection  
- Compared models using RMSE  
- Selected best performing models  

---

### 8. Hyperparameter Tuning  
- Used RandomizedSearchCV for optimization  

---

### 9. Weighted Ensemble Strategy  

Final prediction uses:
- Day-of-week patterns  
- Recent trends (7-day & 30-day averages)  
- Theater-level behavior  
- Fallback:
  - Theater type average  
  - Area average  
  - Global average  

All combined using weighted blending.

---

### 10. Final Output  
- Predictions generated  
- Submission file created  

---

## 🛠️ Tech Stack  

- Python  
- Pandas & NumPy  
- Scikit-learn  
- XGBoost  
- LightGBM  
- Matplotlib & Seaborn  

---

## 📈 Results  

- Ensemble improved stability  
- Time-series features increased accuracy  
- Hybrid approach performed best  

---

## 📌 Future Improvements  

- Add LSTM models  
- Deploy using Flask / FastAPI  
- Build dashboard  

---

## 👨‍💻 Author  

Himanshu  

---

## ⭐ Support  

If you like this project, give it a star ⭐ on GitHub!
