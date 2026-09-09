# 🌾 Smart Farming Crop Yield 2024 – Power BI Dashboard

## 📌 Project Overview

The **Smart Farming Crop Yield 2024 Dashboard** is an interactive **Power BI data analytics project** designed to analyze agricultural data and identify patterns affecting crop yield.

The dashboard provides insights into **crop performance, soil moisture, rainfall, temperature, irrigation methods, crop duration, and NDVI**, helping users understand agricultural productivity and make data-driven farming decisions.

---

## 🎯 Objectives

* Analyze crop yield across different crop types.
* Compare yield based on irrigation methods.
* Study the relationship between rainfall and crop yield.
* Analyze soil moisture and temperature conditions.
* Compare crop performance across different farming conditions.
* Identify important factors affecting agricultural productivity.
* Present insights through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculations
* **Microsoft Excel / CSV** – Dataset
* **Data Visualization & Analytics**

---

## 📊 Key KPIs

The dashboard includes important agricultural KPIs such as:

* 🌱 **Total Farms**
* 🌾 **Total Yield**
* 📈 **Average Yield**
* 💧 **Average Soil Moisture**
* 🌧️ **Average Rainfall**
* 🌿 **Average NDVI**
* 🌡️ **Average Temperature**
* 📅 **Average Crop Duration**

---

## 📈 Dashboard Visualizations

The dashboard contains several interactive visualizations, including:

### 🌾 Crop Type vs Yield

Shows the yield performance of different crop types.

### 💧 Irrigation Type vs Yield

Compares average crop yield across different irrigation methods such as:

* Drip
* Sprinkler
* Manual

### 🌧️ Rainfall vs Yield

A scatter chart used to analyze the relationship between rainfall and crop yield.

### 🌱 Soil Moisture Analysis

Shows how soil moisture varies across farming conditions.

### 🌡️ Temperature Analysis

Helps understand the impact of temperature on crop productivity.

### 🌿 NDVI Analysis

Analyzes vegetation health using the NDVI (Normalized Difference Vegetation Index).

### 📅 Crop Duration

Compares crop growth duration and yield performance.

---

## 🧹 Data Preparation

The dataset was processed using **Power Query** before creating the dashboard.

Main data preparation steps included:

1. Removing unnecessary columns.
2. Handling missing values.
3. Checking and correcting data types.
4. Cleaning categorical values.
5. Standardizing column names.
6. Creating calculated columns where required.
7. Loading the cleaned dataset into Power BI.

---

## 🧮 DAX Measures

Some of the important measures used in the project include:

```DAX
Total Farms = COUNTROWS(Smart_Farming_Crop_Yield_2024)

Total Yield = SUM(Smart_Farming_Crop_Yield_2024[yield_kg_per_hectare])

Average Yield = AVERAGE(Smart_Farming_Crop_Yield_2024[yield_kg_per_hectare])

Average Soil Moisture =
AVERAGE(Smart_Farming_Crop_Yield_2024[soil_moisture_%])

Average Rainfall =
AVERAGE(Smart_Farming_Crop_Yield_2024[rainfall_mm])

Average Temperature =
AVERAGE(Smart_Farming_Crop_Yield_2024[temperature_C])

Average NDVI =
AVERAGE(Smart_Farming_Crop_Yield_2024[ndvi])

Average Crop Duration =
AVERAGE(Smart_Farming_Crop_Yield_2024[crop_duration_days])
```

> **Note:** Adjust the table/column names in the DAX formulas if your dataset uses slightly different names.

---

## 🎛️ Interactive Features

The dashboard includes interactive filters/slicers for exploring the data based on different agricultural parameters.

Users can filter the dashboard to analyze:

* Crop Type
* Irrigation Type
* Soil Conditions
* Farming Conditions
* Other available categorical fields

---

## 💡 Key Insights

The dashboard can be used to identify:

* Which crops have the highest average yield.
* Which irrigation method performs better.
* Whether rainfall has a noticeable relationship with yield.
* How soil moisture varies between farming conditions.
* How temperature affects crop productivity.
* Which farming conditions are associated with better yields.
* Differences in crop duration and productivity.

---

## 📂 Project Structure

```text
Smart-Farming-Crop-Yield-2024/
│
├── Smart_Farming_Crop_Yield_2024 (3).pbix
├── Smart_Farming_Crop_Yield_2024.csv
└── README.md
```

---

## 🖼️ Dashboard Preview

Add screenshots of your Power BI dashboard here.

```markdown
![Smart Farming Dashboard](dashboard.png)
```

You can upload your dashboard screenshot to the GitHub repository and replace `dashboard.png` with the actual image filename.

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Refresh the data if required.
4. Use the slicers and interactive visuals to explore the agricultural data.
5. Analyze crop yield and farming factors through the dashboard.

---

## 📌 Project Type

**Data Analytics | Power BI | Agriculture Analytics | Data Visualization**

---

## 👩‍💻 Author

**Shruti Barokar**

**Skills:**
Power BI • SQL • Excel • Python • Data Analytics • Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star!
