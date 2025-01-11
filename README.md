# Data Science and Analytics Projects

YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Car-Sales_Insurance-Claims_Behaviors/blob/main/notebooks/framework.ipynb) FIRST!

## Table of Contents
1. [Overview](#overview)
2. [Setup](#setup)
3. [Manufacturing Parts Process Analysis](#1-manufacturing-parts-process-analysis)
4. [Motorcycle Parts Sales Analysis](#2-motorcycle-parts-sales-analysis)
5. [Electric Car Charging Habits Analysis](#3-electric-car-charging-habits-analysis)
6. [Car Insurance Claims Prediction](#4-car-insurance-claims-prediction)

## Overview

Applied data science techniques to automotive industry projects, generating actionable insights and optimizing processes in manufacturing, sales, EV charging, and insurance claims prediction.

1. **Manufacturing Parts Process Analysis**: Developed SPC-based monitoring system for manufacturing parts, improving quality control by identifying deviations from control limits.
2. **Motorcycle Parts Sales Analysis**: Analyzed motorcycle parts sales data, generating insights on monthly revenue trends and top-performing product lines across warehouses.
3. **Electric Car Charging Habits Analysis**: Analyzed EV charging habits, identifying peak usage times and optimizing charging station management for increased efficiency.
4. **Car Insurance Claims Prediction**: Developed a predictive model for car insurance claims, identifying driving experience as the top predictor with an accuracy of 77.71%.

## Setup

To replicate the environment used for these projects, use the provided `environment.yml` file to create a conda environment:

```bash
conda env create -f environment.yml
conda activate your_env_name
```

### 1. Manufacturing Parts Process Analysis

**Objective:** Analyze the manufacturing process to determine if it is within acceptable control limits and create alerts for deviations.

**Tools Used:** Python, Pandas, SQLite, SQLAlchemy

**Key Insights:**
- Implemented Statistical Process Control (SPC) to monitor manufacturing parts.
- Identified control limits using SQL window functions.
- Created alerts for parts that fall outside control limits, ensuring high-quality production.


### 2. Motorcycle Parts Sales Analysis

**Objective:** Calculate wholesale net revenue for each product line per month per warehouse.

**Tools Used:** Python, Pandas, SQLite, SQLAlchemy

**Key Insights:**
- Analyzed sales data to determine monthly revenue trends.
- Identified top-performing product lines and warehouses.
- Provided actionable insights for optimizing inventory and sales strategies.


### 3. Electric Car Charging Habits Analysis

**Objective:** Understand EV charging habits to optimize charging station availability.

**Tools Used:** Python, Pandas, SQLite, SQLAlchemy

**Key Insights:**
- Identified garages with the highest number of unique users.
- Determined the most popular charging times.
- Provided recommendations for improving charging station management.



### 4. Car Insurance Claims Prediction

**Objective:** Identify the best predictor of whether a customer will file an insurance claim.

**Tools Used:** Python, Pandas, Statsmodels

**Key Insights:**
- Evaluated multiple features to determine the best predictor.
- Found that driving experience is the most significant predictor of insurance claims.
- Provided a simple yet effective model for predicting claims.
