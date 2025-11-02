# 🔋Driving the Future: AI Powered Data-Driven Predictor and Visualizer for Electric Vehicle Price and Range 

<div align="center">

![Project Banner](https://img.shields.io/badge/ML-Project-green?style=for-the-badge&logo=tensorflow)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red?style=for-the-badge&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**DRIVE SMARTER.PREDICT BETTER.GO ELECTRIC.**

---

### 🎯 Project Impact

```
🌱 Accelerate Green Mobility  |  📊 Enable Fair EV Pricing  |  🚗 Price vs Range Comparison
```

</div>

---

## 🔴 Problem Statement

> **The growing EV market lacks clear and predictive analytics on price and performance of EV.**

### The Challenge

| Current Scenario | The Challenge |
|-----------------|-------------|
| ✅ Rich Ev data available | ❌ No Clear Predictive insights on cost and range |
| ✅ Growing EV adoption | ❌ Hard for consumers to compare performance |
| ✅ Data-Driven Innovation | ❌ Few ML tools analyzing EV market behaviour |

### Our Long Term Goal

Build an **ML-powered system** that can:
- 🎯 Predict the price (Base MSRP)of an EV based on its specs.
- 📈 Estimate its electric range (miles per charge).
- 🔍 Discover relationship between brand ,model ,year and type.
- 💚 Provide actionable insights for consumers, manufacturers and policymakers.

---

## 💡 Solution Overview

```mermaid
graph LR
    A[EV Dataset] --> B[Data Preprocessing]
    B --> C[Feature Engineering]
    C --> D[ML Models]
    D --> E[Predictions]
    E --> F[Interactive Dashboard]

    
    style A fill:#e3f2fd
    style B fill:#fff4e1
    style C fill:#e8f5e9
    style D fill:#f3e5f5
    style E fill:#fce4ec
    style F fill:#fce4ec
```

### Data Insights

| Insight | Obsevation |
|---------|-------------|
| 🔮 **Price Vs Range** | Higher End Model tend to have longer ranges |
| 📊 **Vehicle type** | BEVS outperform PHEVs in range but cost more |
| ⚡ **Manufacturer** | Tesla, BMW, and Nissan dominate high-range segments|
| 🌳 **Model Year** | Newer models show better battery performance |
| 🌳 **CAFV Eligibility** | Incentivized vehicles often have higher efficiency |

---

## ✨ Features

### 🎯 Core Functionality

- **🔢 Price Prediction**
  - Predict EV's base cost (MSRP) using model, type, and year

- **📊 Range Estimation**
  - Predict vehicle's electric range (miles per charge)
  
- **🎨Data Visualization**
  - Interactive EDA showcasing market and manufacturer trends

- **🌱 Feature Engineering**
  - Extract new insights like Price_per_Mile and Vehicle_Age
  
- **🎯 Streamlit Dashboard**
  - Real-time user interface for model predictions
  
- **🔮Multiple ML Models**
  - Random Forest, XGBoost, and Linear Regression comparisons
    
---

## 🏗️ System Architecture

```mermaid
flowchart TB
    subgraph Input["📥  Input Layer"]
        A1[EV Population Dataset]
        A2[User Input Features]
    end
    
    subgraph Processing["⚙️ Processing Layer"]
        B1[Data Cleaning and Preprocessing]
        B2[Encoding And Normalization]
        B3[Normalization]
    end
    
    subgraph ML["🤖 Machine Learning Layer"]
        C1[Linear Regression]
        C2[Random Forest]
        C3[XGBoost]
        C4[Model Evaluation and Selection]
    end
    
    subgraph Output["📤 Output Layer"]
        D1[Predictions Price]
        D2[Predicted Range]
        D3[Visual Insights]
    end
    
    subgraph Deploy["🚀 Deployment"]
        E1[Streamlit App]
        E2[Interactive Dashboard]
    end
    
    A1 --> B1
    A2 --> B1
    B1 --> B2
    B2 --> B3
    B3 --> C1
    B3 --> C2
    B3 --> C3
    C3 --> C4
    C4 --> D1
    C4 --> D2
    D1 --> D3
    D3 --> E1
    E1 --> E2
    
    style Input fill:#e3f2fd
    style Processing fill:#fff3e0
    style ML fill:#e8f5e9
    style Output fill:#f3e5f5
    style Deploy fill:#fce4ec
```

---

## 🔄 ML Pipeline

### Step-by-Step Workflow

```mermaid
graph TD
    A[📂 Data Collection] --> B[🧹 Data Preprocessing]
    B --> C[🔧Exploratory Data Analysis]
    C --> D[✂️Feature Engineering]
    D -->E[🤖 Train-Test Split]
    E --> F[📊 Model Training]
    F --> G{Model Evaluation}
    G --> H[💾 Save Best Model]
    H --> I[🎨 Visualization]
    I --> J[🌐 Streamlit Deployment]
    
    style A fill:#AED581
    style E fill:#64B5F6
    style F fill:#FFD54F
    style H fill:#BA68C8
    style J fill:#F44336
```

### Sample Prediction Formula

```python
#Example derived feature
Price_per_Mile Base_MSRP / Electric_Range

#Example Model Prediction
predicted_pricerf_model.predict(vehicle_features)
```

---




</div>
