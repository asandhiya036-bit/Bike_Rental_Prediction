# 🚲 Urban Bike Rental Demand Analytics & Forecasting Pro

An end-to-end Machine Learning solution to analyze and predict bike sharing demand using **Hourly** and **Daily** datasets. This project leverages **Random Forest Regression** to help urban planners and bike-share operators optimize fleet distribution.

## 🚀 Live Demo
**Interact with the live app here:** https://bit.ly/4s50O7q 

---
## 🎯 Problem Statement

Accurately predicting bike rental demand is essential for ensuring availability and optimizing operations. By forecasting demand, businesses can reduce waiting time and improve customer satisfaction.

## 🎯 Objectives
Analyze bike rental data to identify trends and patterns
Perform data preprocessing and cleaning
Conduct exploratory data analysis (EDA)
Build predictive models for demand forecasting
Evaluate model performance using appropriate metrics

## 📌 Project Overview
Predicting bike rental demand is a complex challenge influenced by weather, time of day, and seasonal trends. This project provides a dual-layered analysis:
1. **Daily Insights**: Understanding long-term seasonal impacts.
2. **Hourly Precision**: Identifying specific rush-hour peaks for real-time fleet management.

---
## 📊 Dataset Description
The project utilizes the UCI Machine Learning Repository's Bike Sharing Dataset:
- **hour.csv**: 17,379 records with hourly features (Temp, Humidity, Windspeed, Hour, etc.)
- **day.csv**: 731 records focusing on daily aggregates and seasonal patterns.

These factors significantly impact bike rental demand and are used for prediction modeling.

## ⚙️ Project Workflow
1. Data Collection
Imported dataset containing rental records
2. Data Preprocessing
Handled missing values
Converted data types
Cleaned and structured data
3. Exploratory Data Analysis (EDA)
Identified trends based on time and season
Analyzed impact of weather conditions
Visualized demand distribution
4. Feature Engineering
Selected relevant variables for prediction
Removed unnecessary features
5. Model Building
Applied regression algorithms to predict demand
Compared model performance
6. Model Evaluation
Evaluated using metrics like:
R² Score
Mean Squared Error
📈 Key Insights
Demand varies significantly based on time and season
Weather conditions strongly affect rental patterns
Peak demand occurs during specific hours of the day

### 🔑 Key Modules:
- **🏠 Dual-Data Dashboard**: Toggle between Daily and Hourly perspectives to view high-level metrics.
- **📊 Demand Heatmaps**: Visualizing peak usage times (Rush hours at 8 AM and 5 PM).
- **🔮 Real-Time Predictor**: A robust forecasting engine where users can input weather and time variables to get instant rental estimates.
- **💡 Operational Strategy**: Data-driven business recommendations for fleet optimization and maintenance scheduling.

---

## 🛠️ Tech Stack
- **Language**: Python 3.10+
- **Framework**: Streamlit
- **Machine Learning**: Scikit-Learn (Random Forest Regressor, Pipeline, ColumnTransformer)
- **Data Handling**: Pandas, Numpy
- **Visualization**: Plotly Express, Matplotlib
- **Deployment**: Streamlit Community Cloud

## 🧪 SDLC Approach

This project follows the Software Development Life Cycle:

Requirement Analysis
Data Processing & Development
Testing and Validation
Result Interpretation
▶️ How to Run
Clone the repository

## Install required libraries:

pip install pandas numpy matplotlib scikit-learn
Open Jupyter Notebook
Run all cells
📌 Future Improvements
Deploy model using a web application (Flask/Streamlit)
Improve accuracy using advanced algorithms (XGBoost, etc.)
Integrate real-time data sources
🤝 Contribution

Contributions are welcome! Feel free to fork and improve this project.

## 📬 Contact

Sandhiya A
📧 asandhiya.036@gmail.com
---
