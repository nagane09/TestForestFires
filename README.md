# Algerian Forest Fire Weather Index (FWI) Prediction 🌲🔥

A Machine Learning project to predict the **Forest Fire Weather Index (FWI)** in Algeria using meteorological data. FWI is a globally recognized metric to estimate wildfire risk based on temperature, humidity, wind, and other environmental factors.

---

## 🚀 Project Overview
This project uses **Ridge Regression** to predict FWI based on features like:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC, DMC, ISI
- Classes
- Region

Higher FWI indicates a higher wildfire risk.

---

## 📊 Highlights
- **Model Used:** Ridge Regression (selected after testing Linear, Lasso, and ElasticNet, which performed lower)
- **Performance:** Achieved **R² score = 0.9843**, demonstrating strong prediction accuracy
- **Data Used:** Algerian Forest Fire dataset (`alegforst.csv`)
- **Feature Scaling:** StandardScaler applied for better model performance
- **Tech Stack:** Python, Flask, Scikit-learn, Pickle, HTML/CSS
- **Deployment:** Render

---

## 💡 Key Learnings
1. Data preprocessing and feature scaling for regression models  
2. Comparing different regression models to select the best one  
3. Integrating ML models with a full-stack application  
4. Handling user inputs via a web interface  
5. Deploying Python ML applications on the cloud  

---

## ⚙️ How to Use
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/ForestFireFWI.git
