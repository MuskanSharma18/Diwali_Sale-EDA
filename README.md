# Diwali Sales Analysis

This project performs an analysis of Diwali sales data, exploring customer demographics, product preferences, and insights into the most popular categories of products purchased. The analysis aims to identify trends and key customer segments, which can help in understanding the buying behavior during the Diwali season.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Conclusions](#conclusions)

## Project Overview

The project focuses on analyzing sales data during the Diwali season. It explores key metrics such as:
- Customer demographics (age, gender, marital status)
- Product categories sold (e.g., Electronics, Food, Clothing)
- State-wise and occupation-wise sales distributions

Through visualizations, this analysis uncovers patterns, helping to make informed business decisions for future sales campaigns.

## Features

- **Data Cleaning:** Ensures that the dataset is clean and ready for analysis by handling missing values and outliers.
- **Data Visualization:** Generates various plots such as bar charts and pie charts to provide insights into sales patterns.
- **Customer Segmentation:** Analyzes customer demographics like age, gender, and occupation to identify the most relevant customer segments.
- **Product Analysis:** Identifies the most popular product categories and product IDs.

## Installation

To set up the project, follow these steps:

1. **Clone the repository:**
2. **Navigate to the project directory:**

   ```bash
   cd diwali-sales-analysis
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   The main dependencies include:
   - `pandas`
   - `numpy`
   - `matplotlib`
   - `seaborn`
   - `plotly`

4. **Launch Jupyter Notebook:**

   Run the following command to start Jupyter Notebook and open the project notebook.

   ```bash
   jupyter notebook
   ```

## Usage

1. Load the dataset by running the notebook cells. The dataset should be in CSV format (e.g., `diwali_sales_data.csv`).
2. Follow the steps in the notebook to visualize various aspects of the Diwali sales data.
3. Analyze customer demographics, product preferences, and other insights as displayed in the notebook outputs.

## Data

The project requires a dataset that contains information such as:
- Customer demographics (age, gender, occupation, state, marital status)
- Products purchased (product ID, category, price)
- Transaction details (transaction ID, date)

The sample dataset can be modified or replaced based on your specific sales data.

## Results

Key insights from the analysis:
- **Top Selling Products:** A breakdown of the most purchased products by category.
- **Customer Segmentation:** Married women aged 26-35 from UP, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the primary buyers.
- **Product Preferences:** Popular categories include Food, Clothing, and Electronics.
  
The visualizations in the notebook help in better understanding these insights.

## Conclusions

The analysis reveals that Diwali sales are driven by a specific customer segment—primarily married women aged 26-35 working in IT, Healthcare, and Aviation. This insight can assist in targeting future marketing efforts. The popular product categories during Diwali are Food, Clothing, and Electronics.
