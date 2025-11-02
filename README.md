# 🏠 Smart HVAC Energy Prediction using Machine Learning

### 🌍 Sustainable Energy Management using AI

This project applies **Machine Learning (ML)** and **Data Analysis in Python** to predict the **energy consumption of HVAC (Heating, Ventilation, and Air Conditioning)** systems based on environmental and temporal conditions.

By accurately forecasting HVAC energy usage, buildings can **optimize power consumption**, reduce **carbon emissions**, and support **sustainable energy practices** — directly aligning with **green engineering goals**.

---

## 🔍 Project Overview

### 🎯 Objective
Develop a machine learning model that predicts **energy consumption** (in Wh) of home appliances (mainly HVAC systems) using:
- Indoor & outdoor **temperature** and **humidity**
- **Time of day** and **day of week**
- Weather-related features

The model helps **smart buildings** or **facility managers** plan energy usage efficiently and minimize waste.

---

## 🧠 Key Features
- Applies **AI/ML techniques (Regression models, CNN-ready data)** for predictive analysis  
- Promotes **sustainable energy management** practices  
- Built entirely with **Python (NumPy, Pandas, Matplotlib, Scikit-learn, Seaborn)**  
- Executed in a **Jupyter Notebook environment**  
- Trained using the **UCI “Appliances Energy Prediction” dataset**

---

## 🗂️ Dataset Details

**Source:** [UCI Machine Learning Repository — Appliances Energy Prediction Dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction)

- **File:** `energydata_complete.csv`
- **Records:** ~20,000
- **Features:**
  - Indoor and outdoor temperature/humidity sensors
  - Weather conditions
  - Time-based features (date, hour, weekday)
- **Target Variable:** `Appliances` (energy consumption in Wh)

---

## ⚙️ Environment Setup

### 1️⃣ Create Virtual Environment
```bash
python -m venv hvac-env
source hvac-env/bin/activate   # Mac/Linux
hvac-env\Scripts\activate      # Windows
