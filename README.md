# Agriculture-Crop-Production-Yield-Prediction
📌 Project Overview

This project focuses on analyzing and predicting agricultural crop production and yield using district-level historical data from India (1966–2017).
The study helps understand how crop area, production, and yield have changed over time and how they are interrelated.

The project applies Exploratory Data Analysis (EDA), statistical correlation, and basic machine learning concepts to derive insights useful for farmers, researchers, and policymakers.

🎯 Problem Statement

Agricultural production depends on multiple factors such as:

Cultivation area

Crop type

District and state

Year

The objective is to:

Analyze historical trends

Identify relationships between crop variables

Build a foundation for predicting crop production and crop yield

📂 Dataset Information

Rows: 3168

Columns: 14

Key Attributes

Dist Code, Dist_Name, State_Name

Year

RICE AREA (1000 ha)

RICE PRODUCTION (1000 tons)

RICE YIELD (Kg/ha)

GROUNDNUT AREA / PRODUCTION / YIELD

SUGARCANE AREA / PRODUCTION / YIELD

FRUITS AND VEGETABLES AREA (1000 ha)

🧹 Data Cleaning & Preprocessing

The following steps were performed:

Removed unnecessary column (State Code)

Renamed columns for clarity

Checked for missing values (none found)

Selected numeric columns for correlation analysis

Prepared dataset for visualization and modeling

📊 Exploratory Data Analysis (EDA)
Key Insights

Rice area shows strong correlation with rice production

Crop yields have improved steadily over the years

Groundnut and sugarcane show region-dependent variations

Fruits & vegetables cultivation area has increased over time

📈 Visualizations Included

Correlation heatmap

Pair plots for:

Year

State

District

Crop area, production, and yield

Box plots for outlier detection

Bar charts:

State-wise crop yield

Year-wise yield comparison

District-level comparisons

🌱 Crop-wise Analysis
🌾 Rice

Strong positive correlation between area and production

Yield has increased consistently over years

🌰 Groundnut

Moderate production levels

Yield varies significantly by region

🍬 Sugarcane

Smaller cultivation area

Very high production and yield

Strong correlation between area and production

🤖 Machine Learning Objective

The project sets the base for two predictive tasks:

🔹 Model 1: Crop Production Prediction

Inputs:

Year

Crop Area

Crop Yield

Target:

Crop Production

🔹 Model 2: Crop Yield Prediction

Inputs:

Year

Crop Area

Crop Production

Target:

Crop Yield

(Regression-based approach)

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📁 Project Structure
├── Agriculture Prediction.ipynb
├── Agriculture Crop Production.pdf
├── README.md
└── Dataset (SIADataset.csv)

✅ Conclusion

This project demonstrates how data science techniques can be applied to agriculture to:

Analyze long-term trends

Understand crop behavior

Support data-driven decision-making

🚀 Future Enhancements

Include rainfall, soil, and climate data

Apply advanced ML models (Random Forest, XGBoost)

Time-series forecasting

Build an interactive dashboard

Deploy as a web application

👤 Author

Karthick Seenivasan

Dhanavandhan
