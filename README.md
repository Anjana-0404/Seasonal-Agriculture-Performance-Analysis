# Seasonal Agriculture Performance Analysis

## 📌 Project Overview
The **Seasonal Agriculture Performance Analysis** project investigates how farming outcomes, crop productivity, resource consumption, and economic returns vary across distinct agricultural cycles—**Kharif**, **Rabi**, and **Zaid**. By analyzing environmental metrics (rainfall, temperature, soil moisture, humidity), operational inputs (fertilizers, pesticides, irrigation methods), and farm-level economics, this project identifies critical seasonal patterns and provides actionable, data-driven recommendations for optimized farm planning and sustainable resource allocation.

---

## 🚀 Key Objectives
- **Data Preprocessing & Cleaning:** Handle missing values using season-aware group imputations and normalize agricultural indicators.
- **Seasonal Performance Benchmarking:** Evaluate disparities in yield (`Yield_Tonnes_Ha`), production volume, total costs, and net farm profitability across seasons.
- **Resource & Water Efficiency:** Quantify water productivity (`t/1,000 m³`) across varied irrigation techniques (Drip, Sprinkler, Flood, Rainfed)[cite: 1, 2].
- **Environmental & Disease Dynamics:** Assess the correlation between weather parameters, pest/disease risk vulnerabilities, and crop output[cite: 1, 2].
- **Data-Driven Strategic Recommendations:** Provide evidence-based insights for crop rotation, input cost rationalization, and irrigation scheduling[cite: 1, 2].

---

## 📊 Dataset Description
The dataset contains **4,000 records** across **28 features** capturing agricultural activities in India[cite: 1, 2]:

| Category | Key Attributes |
| :--- | :--- |
| **Geographic & Categorical** | `Farm_ID`, `State`, `District`, `Crop`, `Season`, `Irrigation_Method` |
| **Environmental & Weather** | `Rainfall_mm`, `Avg_Temperature_C`, `Humidity_pct`, `Sunlight_Hours_Day` |
| **Soil & Agronomic Inputs** | `Soil_pH`, `Soil_Moisture_pct`, `Nitrogen_kg_ha`, `Phosphorus_kg_ha`, `Potassium_kg_ha`, `Fertilizer_kg_ha`, `Pesticide_Litre_ha`, `Seed_Quality_Score` |
| **Production & Performance**| `Farm_Area_Hectares`, `Yield_Tonnes_Ha`, `Production_Tonnes`, `Disease_Pest_Risk_pct` |
| **Economic & Financials** | `Market_Price_INR_Tonne`, `Total_Cost_INR`, `Revenue_INR`, `Profit_INR` |
| **Resource Efficiency** | `Water_Used_m3`, `Water_Efficiency_t_per_1000m3` |

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.10+
- **Environment:** Google Colab / Jupyter Notebook[cite: 1, 2]
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`

---

## 📁 Repository Structure
```text
├── data/
│   └── seasonal_agriculture_performance_dataset.csv     # Agricultural dataset
├── notebooks/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb  # End-to-end Colab notebook
├── images/                                               # Generated plots and charts
├── README.md                                             # Project documentation
└── requirements.txt                                      # Python dependencies
