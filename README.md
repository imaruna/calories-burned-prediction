# Calories Burned Prediction from Running Data

This project analyzes fitness tracking data from two separate datasets filtered for **running activities** to build predictive models for calorie expenditure.  
The analysis was performed in **R**, using both **Linear Regression** and **Ridge Regression** to estimate calories burned based on multiple running-related variables.

---

## Project Overview
- **Goal**: Predict calories burned during running sessions using personal and environmental factors.
- **Data Sources**:
  - Dataset 1: Collected by Lucas (running activities, heart rate, distance, pace, etc.)
  - Dataset 2: Collected by Dakota (similar variables plus weather conditions)
- **Approach**:
  1. Cleaned and merged datasets
  2. Filtered to include only running activities
  3. Explored variables such as **distance, average heart rate, pace, and weather**
  4. Built and evaluated Linear and Ridge Regression models
  5. Visualized results and presented findings in an HTML report

---

## Technologies Used
- **R (Programming Language)**
- **tidyverse** — Data cleaning and manipulation
- **ggplot2** — Data visualization
- **caret** — Model building and evaluation

---

## Results
- Both models were able to predict calorie expenditure with reasonable accuracy
- Ridge Regression slightly improved performance by reducing overfitting
- Key predictive factors included **distance**, **average heart rate**, and **pace**
- Weather conditions provided additional but smaller predictive value

---

## 📂 Repository Structure
