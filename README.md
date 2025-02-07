# 🚀 Fuel Economy Analysis - Predicting Urban Fuel Consumption (UCity)

## 📌 Project Overview

This project analyzes fuel economy data to understand urban fuel consumption (UCity) patterns. Using Exploratory Data Analysis (EDA) and Machine Learning, we identify key factors affecting fuel efficiency and predict UCity values based on vehicle features.

## 📊 Dataset Information

Source: U.S. Department of Energy - Fuel Economy Dataset (https://www.fueleconomy.gov/)

Records: 40,081 vehicles

Features: Vehicle specs, fuel types, engine details, and CO2 emissions

📂 Repository Structure

📦 Fuel-Economy-Analysis
 ┣ 📂 images               # Visualizations from the notebook
 ┣ 📜 main.ipynb           # Jupyter Notebook with EDA & ML Model
 ┣ 📜 README.md            # Project Documentation
 ┣ 📜 requirements.txt     # Dependencies (Optional)
 ┗ 📜 vehicles.csv         # Dataset (Add in .gitignore if too large)

🔍 Analysis & Key Findings

✅ Exploratory Data Analysis (EDA)

Identified missing values and cleaned dataset

Boxplots, histograms, and bar charts used to visualize fuel consumption trends

Strong correlation found between UCity and features like displ (engine displacement) & cylinders




✅ Feature Engineering

One-hot encoding applied to categorical variables (fuelType, drive, VClass)

Created engine efficiency metric (displ / cylinders)

Removed highly correlated redundant features

✅ Machine Learning Model

Built Regression Models to predict UCity

Used Linear Regression, Random Forest, and XGBoost

Best Model: Random Forest Regression (R² = 0.85, RMSE = 2.3)

⚙️ How to Run the Notebook

Clone this repository:

git clone https://github.com/yourusername/Fuel-Economy-Analysis.git
cd Fuel-Economy-Analysis

Install dependencies:

pip install -r requirements.txt

Open and run the Jupyter Notebook:

jupyter notebook main.ipynb

🔮 Future Improvements

Optimize model hyperparameters for better accuracy

Include more external datasets for better generalization

Deploy model as a web API for real-time fuel efficiency predictions

📌 Author: Your Name📧 Contact: your.email@example.com⭐ If you found this useful, give it a star! 🌟
