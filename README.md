# Smart Home Energy Analysis – Week 1  

This project analyzes Smart Home energy usage recorded every 15 minutes across different appliances and activities as part of Week-1 milestone: **Data Integration + Pre-processing + EDA**.

---

## 📌 Dataset Overview  

Source (Kaggle):  
🔗 https://www.kaggle.com/datasets/taranvee/smart-home-energy-tracking  

Dataset contains:
- 10 homes  
- 12 months duration  
- 5 appliances (AC, TV, Washer, Fridge, Light)  
- Interval: every 15 minutes  

Main columns:
`timestamp, device_type, activity, power_watt, indoor_temp, outdoor_temp, status, user_present`

---

## ✔ Key Steps Completed (Week-1)

### 🔹 Data Preparation
- Loaded dataset (.csv)
- Converted timestamp to datetime format
- Checked datatypes
- Checked missing values (no nulls found)
- Verified timestamp interval (consistently 15-minute logs)

### 🔹 Feature Engineering
Energy consumption computed as:

---

## 📊 Exploratory Analysis Completed
EDA includes visual analysis of:
- Energy per device
- Energy per activity
- User presence vs energy use
- Device status (on/off)
- Hourly and weekday patterns

---

## ⚖ Balanced Sampling (Equal Samples)
Balanced datasets created for:
- status (on/off)
- user_present (yes/no)
- activity (5 categories)

Balanced subset CSVs saved and used for fair comparison plots.

---

## 📁 Outputs
All figures (PNG plots) available in:
