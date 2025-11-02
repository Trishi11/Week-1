#  Smart HVAC Energy Prediction using Machine Learning

### Sustainable Energy Management using AI

This project applies **Machine Learning (ML)** and **Data Analysis in Python** to predict the **energy consumption of HVAC (Heating, Ventilation, and Air Conditioning)** systems based on environmental and temporal conditions.

By accurately forecasting HVAC energy usage, buildings can **optimize power consumption**, reduce **carbon emissions**, and support **sustainable energy practices** — directly aligning with **green engineering goals**.

---

## Project Overview

###  Objective
Develop a machine learning model that predicts **energy consumption** (in Wh) of home appliances (mainly HVAC systems) using:
- Indoor & outdoor **temperature** and **humidity**
- **Time of day** and **day of week**
- Weather-related features

The model helps **smart buildings** or **facility managers** plan energy usage efficiently and minimize waste.

---

## Key Features
- Applies **AI/ML techniques (Regression models, CNN-ready data)** for predictive analysis  
- Promotes **sustainable energy management** practices  
- Built entirely with **Python (NumPy, Pandas, Matplotlib, Scikit-learn, Seaborn)**  
- Executed in a **Jupyter Notebook environment**  
- Trained using the **UCI “Appliances Energy Prediction” dataset**

---

## Dataset 

**Source:** [UCI Machine Learning Repository — Appliances Energy Prediction Dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction)

- **File:** `energydata_complete.csv`
- **Records:** ~20,000
- **Features:**
  - Indoor and outdoor temperature/humidity sensors
  - Weather conditions
  - Time-based features (date, hour, weekday)
- **Target Variable:** `Appliances` (energy consumption in Wh)

---

## Environment Setup

### Create Virtual Environment
```bash
python -m venv hvac-env
source hvac-env/bin/activate   # Mac/Linux
hvac-env\Scripts\activate      # Windows
```

### Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

### Launch Jupyter Notebook
jupyter notebook

---

 Example Insights

Energy consumption increases during morning and evening hours.

High outdoor temperatures trigger higher HVAC energy usage.

Weekdays show different consumption trends than weekends.

---

### Sustainability Impact

This project demonstrates how AI/ML can drive sustainability by:

Predicting and optimizing energy usage

Reducing wasteful HVAC operation

Supporting green building automation systems
---

### Tools & Technologies
---
Category	Tools/Frameworks
Programming	Python 3.x
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Environment	Jupyter Notebook
Dataset	UCI Energy Data
ML Task	Regression / Forecasting


### References

UCI ML Repository – Appliances Energy Prediction Dataset

Scikit-learn Documentation

Matplotlib & Seaborn Docs


### Status

 Week 1 completed: Data cleaning, visualization, and train-test split




Project by: Trishika Shrivastav
Duration: 1 week
Focus: AI for Sustainable Energy Optimization
