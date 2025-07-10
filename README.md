# YBI Foundation Internship Project

## Description

This repository contains a data science project focused on **estimating the cost of agricultural equipment** using real-world data. The project leverages a Jupyter Notebook and a comprehensive dataset to help users understand data analysis, feature engineering, and predictive modeling in the context of farm equipment valuation.

## Repository Structure

- `YBI_Foundation_Internship_Project.ipynb`: Main Jupyter Notebook containing all code, analysis, and results.
- `Farm Equipment Cost Estimation for KrishiTech.csv`: Dataset with detailed records of agricultural equipment.

## Dataset Overview

The dataset consists of **1,000 entries** with the following columns:

| Column                   | Description                                   |
|--------------------------|-----------------------------------------------|
| equipment_type           | Type of equipment (e.g., Tractor, Harvester)  |
| brand                    | Brand name (e.g., TAFE, Mahindra)             |
| year_of_manufacture      | Year the equipment was manufactured           |
| condition_rating         | Condition score (0-10 scale)                  |
| usage_hours              | Total hours the equipment has been used        |
| current_market_trend     | Market trend factor for price adjustment      |
| resale_history_factor    | Factor based on resale history                |
| estimated_cost_inr       | Estimated cost in Indian Rupees               |

### Sample Data

| equipment_type     | brand      | year_of_manufacture | condition_rating | usage_hours | current_market_trend | resale_history_factor | estimated_cost_inr |
|--------------------|------------|---------------------|------------------|-------------|---------------------|----------------------|--------------------|
| Tractor            | TAFE       | 2018                | 9.73             | 1043        | 0.86                | 1.01                 | 370,794            |
| Rotavator          | John Deere | 2001                | 2.28             | 50          | 1.19                | 0.83                 | 23,726             |
| Combine Harvester  | TAFE       | 2016                | 4.61             | 531         | 1.19                | 1.02                 | 602,054            |

### Dataset Highlights

- **Total Entries:** 1,000
- **Distinct Equipment Types:** 6
- **Distinct Brands:** 6
- **Year Range:** 2000–2023
- **Average Condition Rating:** 5.6
- **Average Usage Hours:** 1,022
- **Average Estimated Cost:** ₹127,512

## Valuable Insights from the Notebook

- **Data Exploration:** The notebook performs in-depth data cleaning and exploratory analysis, including equipment age distribution, condition ratings, and brand popularity.
- **Feature Engineering:** Key features such as market trends and resale history are incorporated to enhance prediction accuracy.
- **Modeling:** A regression model is trained to estimate equipment costs based on input features.
- **Performance Metrics:** The model achieves strong predictive performance, making it useful for both buyers and sellers in the agricultural market.
- **Sample Prediction:** The notebook demonstrates how to predict the estimated value for new equipment entries based on user-provided features.

## Installation & Setup

Copy and run these commands in your terminal to set up the project:

`` git clone https://github.com/RahulSingh005/YBI.git ``

`` cd YBI ``

## Usage

- Open the Jupyter Notebook:
jupyter notebook YBI_Foundation_Internship_Project.ipynb
- Follow the notebook to understand data processing, modeling, and how to make your own predictions.
- Use the dataset for further experiments or learning.

## Contributing

- Fork the repository.
- Create a new branch for your feature or bugfix.
- Submit a pull request with a clear description of your changes.
