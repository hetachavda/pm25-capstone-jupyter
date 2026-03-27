# 🌍 PM2.5 Air Pollution Analysis & Prediction

## 📌 Project Overview
This project analyzes and predicts PM2.5 air pollution levels across Canadian cities using real-world data from the National Air Pollution Surveillance (NAPS) dataset (2020–2023).

The objective is to transform environmental data into actionable insights and predictive models to support decision-making in public health and smart-city systems.

---

## 🎯 Objectives
- Analyze PM2.5 trends across cities and seasons  
- Clean and preprocess large-scale air quality datasets  
- Build predictive models for forecasting  
- Compare machine learning and time-series approaches  
- Evaluate the impact of secondary pollutants (NO₂, SO₂, O₃)  

---

## ⚙️ Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)  
- ARIMA, SARIMA, SARIMAX  
- Linear Regression, Decision Tree, Random Forest  
- Matplotlib, Power BI  
- Jupyter Notebook  
- Git & GitHub  

---

## 📊 Key Insights
- PM2.5 shows seasonal variation, generally higher in winter  
- Linear Regression achieved the best baseline performance  
- Time-series models showed potential but were limited by missing meteorological data  
- NO₂ showed the strongest relationship with PM2.5  
- Prediction accuracy decreases during extreme pollution events  

---

## 🤖 Models Implemented
- Linear Regression  
- Decision Tree  
- Random Forest  
- ARIMA  
- SARIMA  
- SARIMAX  

---

## 📁 Project Structure

```
pm25-capstone-jupyter/
│
├── data/
├── notebooks/
├── outputs/
├── README.md
```

## 📈 Key Results
- Best Model: Linear Regression  
- RMSE: ~13.5  
- R²: ~0.55  
- SARIMAX improved performance with exogenous variables  

---

## ⚠️ Limitations
- Meteorological data not included  
- Seasonality not fully decomposed  
- Lower accuracy during extreme pollution events  

---

## 🚀 Future Improvements
- Add weather data (temperature, wind, humidity)  
- Apply advanced models (XGBoost, LSTM)  
- Improve extreme event prediction  
- Deploy real-time dashboard  

---

## 👨‍💻 Authors
**Heta Chavda**  
Master of Data Analytics | University of Niagara Falls  

**Jaya Parekh**  
Project Contributor  

---

## 🔗 Repository
https://github.com/hetachavda/pm25-capstone-jupyter
