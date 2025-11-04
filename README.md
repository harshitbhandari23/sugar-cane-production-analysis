🌾 Sugarcane Production Analysis
📌 Overview

This project performs a data analysis of global sugarcane production using Python.
The dataset includes information about:

Countries and their continents

Sugarcane production (in tons)

Acreage used (in hectares)

Yield (Kg per hectare)

Production per person

The analysis includes data cleaning, visualization, and insights extraction using libraries like Pandas, NumPy, Matplotlib, and Seaborn.

🧩 Libraries Used
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

🧹 Data Cleaning Steps

Removed special characters like dots (.) and commas (,) from numeric columns.

Converted string columns to numeric (float) types.

Dropped null and unwanted columns like index and Unnamed: 0.

Verified data consistency and structure using df.info() and df.describe().

📊 Univariate Analysis

Continent-wise count of sugarcane-producing countries
Used countplot() to visualize distribution across continents.

Distribution of numeric variables
Created histograms and boxplots for:

Production (Tons)

Acreage (Hectare)

Production per Person (Kg)

Yield (Kg / Hectare)

📈 Bivariate Analysis

Pie Chart: Country-wise contribution to total production.

Bar Charts:

Top countries by acreage.

Top countries by yield.

Top producers by total production.

Heatmap: Correlation matrix to understand relationships between production, acreage, and yield.

Jointplot: Relationship between land area and production.

🧠 Key Insights

Country with Most Land:

The dataset revealed the country with the highest sugarcane cultivation area.

Country with Highest Yield per Hectare:

Identified top 5 high-yield countries.

Country with Highest Production:

The top sugarcane-producing nations were highlighted using barplots.

Correlation Findings:

✅ Countries with more land tend to produce more sugarcane.

❌ Higher yield per hectare does not necessarily mean higher total production.

🌍 Continent-Level Analysis

Grouped by Continent to find total production and average yield.

Added country count per continent to compare number of producers vs. total production.

Findings:

❌ The number of countries in a continent does not directly affect sugarcane production.

✅ Continents with larger cultivated land areas produce more sugarcane overall.

🔥 Visual Highlights

Seaborn Heatmap for correlation

Bar charts showing top producers

Pie chart illustrating production share per country

Jointplot showing Production vs. Acreage relationship

🧰 Tools & Technologies
Tool	Purpose
Python	Programming language
Pandas	Data manipulation
NumPy	Numerical computations
Matplotlib & Seaborn	Data visualization
CSV Dataset	Input data source
🧾 Conclusion

This analysis provides valuable insights into global sugarcane production trends.
It helps in understanding how land usage and regional distribution influence total production and yield efficiency.

📁 Project Structure
├── List of countries by Sugarcane Production.csv
├── sugarcane_analysis.ipynb
├── README.md

📸 Sample Visuals

Barplot: Top 10 Countries by Acreage

Heatmap: Correlation among Production Metrics

Pie Chart: Country-wise Sugarcane Production Share
