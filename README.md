# 🚗 Used Car Analysis & Interactive Search System

An end-to-end Data Analysis project that processes a large-scale used car dataset (over 426K entries) and provides an interactive web application for searching and visualizing market trends.

## 📋 Project Overview
This project was developed as part of my Data Analysis journey. It involves cleaning a messy real-world dataset and building a tool that helps users find the best car deals based on specific criteria.

## ✨ Key Features
- **Data Cleaning:** Handled missing values using logical imputation (e.g., filling 'condition' based on price means).
- **Feature Engineering:** Extracted useful features like `origin_country`, `posting_weekday`, and `vehicle_age`.
- **Interactive Search:** A Streamlit-based dashboard to filter cars by:
  - Manufacturer
  - Price Range
  - Manufacturing Year
  - Car Condition
- **Dynamic Visualization:** Real-time charts that update based on search results (Price distribution and vehicle type counts).

## 🛠️ Technologies Used
- **Python** (Core language)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Streamlit** (Web Application Framework)

## 📂 Project Structure
- `New_Data.csv`: The cleaned dataset used by the app.
- `code.py`: The main Streamlit application script.
- `Used_car_Analysis.ipynb`: The original Jupyter Notebook containing the cleaning and EDA process.

## 🚀 How to Run the Project
1. Clone this repository or download the files.
2. Install the required libraries:
   ```bash
   pip install streamlit pandas seaborn matplotlib