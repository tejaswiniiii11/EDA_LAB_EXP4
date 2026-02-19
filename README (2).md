# VISUAL ENCODING OF TRAFFIC ACCIDENT DATA USING R

**Name:** Tejaswini M  
**Register Number:** 23BAD121  
**Course:** Exploratory Data Analysis & Visualization

----------------------------------------------

## 📌 Project Overview

This project applies effective visual encoding principles to improve meaningful data communication.

A city traffic department analyzes accident records to identify high-risk zones and understand accident severity patterns. Proper visual encoding enables multiple variables to be represented simultaneously within a single visualization for clearer exploratory analysis.

This lab demonstrates how color, size, and shape can effectively encode different accident attributes.

-------------------------------------------------

## 🗂️ Dataset Information

**File Name:** `4.traffic_accidents.csv`  
**Type:** CSV file containing traffic accident records  

-------------------------------------------------

## 📄 Key Attributes

- **Accident_ID** – Unique identifier for each accident  
- **Vehicles_Involved** – Number of vehicles involved  
- **Severity** – Level of accident severity (Minor, Major, Fatal)  
- **Casualties** – Number of injured or deceased individuals  
- **Accident_Type** – Type/category of accident  

The dataset supports exploratory analysis of accident severity and frequency patterns.

-------------------------------------------------

## 🛠️ Tools & Libraries Used

### Software
- R  
- RStudio  

### Libraries
- `ggplot2` – Data visualization  
- `dplyr` – Data preprocessing and transformation  

------------------------------------------------

## ⚙️ Implementation Steps

### 1️⃣ Data Loading & Preparation

- Imported dataset using `read.csv()`  
- Examined structure using `str()` and `summary()`  
- Converted `Severity` into ordered factor (Minor < Major < Fatal)  
- Converted `Accident_Type` into categorical variable  

------------------------------------------------

### 2️⃣ Visual Encoding Principles Applied

#### 🎨 Color Encoding (Severity)

- Minor → Yellow  
- Major → Orange  
- Fatal → Red  
- Stronger colors indicate higher severity levels.

#### 📏 Size Encoding (Casualties)

- Mapped number of casualties to point size.  
- Larger points represent accidents with greater impact.

#### 🔺 Shape Encoding (Accident Type)

- Different shapes indicate different accident categories.  
- Allows differentiation between accident types within the same plot.

------------------------------------------------

## 📊 Visualization Created

Multi-variable scatter plot with:

- **X-axis:** Number of Vehicles Involved  
- **Y-axis:** Accident ID  
- **Color:** Severity level  
- **Size:** Number of casualties  
- **Shape:** Accident type  

This combined encoding approach enables efficient exploratory data analysis of traffic risk patterns.

------------------------------------------------

## 📈 Visualizations Generated

- Multi-encoded scatter plot showing accident severity, type, and casualty distribution  

All visualizations were created using `ggplot2`.

------------------------------------------------

## 🎯 Key Insights

- Fatal accidents stand out through high-intensity color encoding.  
- High-casualty incidents are immediately identifiable through size scaling.  
- Visual encoding allows multiple accident dimensions to be analyzed simultaneously.  

This exercise reinforces the importance of thoughtful visual encoding in exploratory data analysis.

