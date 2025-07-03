# Edunet_ML_Project-Glacier-Melt-Rate
 This case study addresses the accelerating rate of glacier melting, which significantly contributes to sea-level rise and climate change. The aim is to use machine learning models to predict glacier melt rates based on various environmental and geographical parameters.

# ❄️ Glacier Melt Rate Prediction using Machine Learning

 ---

## 📌 Overview

Glaciers are melting at an alarming rate due to climate change, contributing significantly to sea-level rise.  
This project leverages **Machine Learning** (ML) to predict glacier melt rates based on multiple environmental and geographical features.

We implemented a **Linear Regression** model to analyze and forecast melt rates using a synthetic dataset,  
helping visualize trends and understand the primary drivers behind glacial melting.

---

## 🎯 Objectives

- ✅ Predict glacier melt rates using ML regression algorithms  
- ✅ Identify critical features influencing melting (e.g., temperature, CO₂ levels)  
- ✅ Visualize regional melting trends  
- ✅ Evaluate model performance using MSE, RMSE, and R² metrics  

---

## 🧠 Machine Learning Approach

### 📂 Dataset Description

| Feature                | Description                                     |
|------------------------|-------------------------------------------------|
| AvgAnnualTemperature   | Mean annual temperature (°C)                    |
| CO2Concentration       | Atmospheric CO₂ levels (ppm)                    |
| AnnualPrecipitation    | Yearly precipitation (mm)                       |
| GlacierArea            | Surface area of glacier (km²)                   |
| MeanElevation          | Average elevation of glacier (m)                |
| SolarRadiation         | Incoming solar radiation (W/m²)                 |
| Albedo                 | Surface reflectivity (0–1)                      |
| Latitude               | Geographic latitude                             |
| Region                 | Geographical region (Himalayas, Alps, etc.)     |
| GlacierType            | Type of glacier (e.g., Valley, Continental)     |
| **MeltRate (target)**  | Annual melt rate of glacier                     |

> 📦 Dataset Size: **2000 records**  
> 📌 Source: Synthetic dataset created for academic use (ChatGPT-generated)

---

## 🛠️ Methodology

1. **Load and Clean Data**  
2. **Encode Categorical Features** (Region, GlacierType)  
3. **Split Data** – Train/Test using `train_test_split`  
4. **Model Training** – Linear Regression (`sklearn.linear_model`)  
5. **Evaluation** – MSE, RMSE, R²  
6. **Visualization** – Seaborn + Matplotlib plots to display melt rate trends by region  

---

## 📈 Results

- ✅ **R² Score**: ~0.70  
- ✅ Visualized regional melt rate distribution  
- ✅ Histogram with KDE plot for predicted melt rates  
- 🔍 Identified strong correlation with Avg Temperature and CO₂ concentration  

---

## 📊 Visualization Example

> 🧾 
![Prediction histogram](https://github.com/user-attachments/assets/8be20628-ff0c-4cad-b876-7741e0acb07a)

---

 
### 📍  **Students**:
              Roshan Ramchandra Patil  
              Antara Rajendra Sarvade

---
