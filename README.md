#CARBON EMISSION USING ML 


# 🌱 GreenAI Carbon Emission Predictor

Welcome to the **GreenAI Streamlit App**, a smart and interactive tool to estimate and visualize **carbon emissions for Indian cities** based on sustainability metrics.

## 🚀 Overview

This web app uses machine learning (Random Forest Regression) to predict **total CO2 emissions (in kilotons)** for Indian cities. It integrates visual insights like:

- 📊 Feature Importance
- 📍 Folium Map of CO2 by City
- 🌀 Radar Charts for Metrics
- 🧬 Correlation Heatmap
- 📈 Trends and Scatter Visuals
- 🥧 Pie & Bar Charts for Top Cities
- 🧠 Model trained on features like energy use, transport impact, green space & more

---

## 🔧 How It Works

1. Input values for 12 sustainability metrics via sidebar sliders.
2. The app predicts total CO2 emission using a pre-trained ML model.
3. Visualizations dynamically update based on your input.
4. City-level map and trends help understand emission patterns.

---

## 📁 Files Included

- `app.py` – Streamlit app source code
- `carbonemission.csv` – Dataset used
- `greenai_carbon_model.pkl` – Trained ML model
- `scaler.pkl` – StandardScaler for input normalization
- `requirements.txt` – Python dependencies

---

## 📦 Dependencies

The app requires the following libraries:

```txt
streamlit
pandas
numpy
scikit-learn
joblib
seaborn
matplotlib
plotly
folium
streamlit-folium
