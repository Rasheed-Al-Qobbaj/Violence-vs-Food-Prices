# Analyzing the Impact of Violence on Food Prices in Palestine

This repository contains a Jupyter Notebook that explores the effects of political violence on food prices in Palestine. The analysis is part of my Data Science course project.

## Description

Food prices and political stability are often interlinked. This project investigates how violent events impact the cost of essential commodities, using datasets from Palestine covering both Gaza and the West Bank.

### Datasets

1. **Food Prices Dataset (`palestine_food_prices.csv`)**  
   - Records detailed food price data in Palestine across multiple years.  
   - Includes attributes such as date, region, city, market location (latitude and longitude), commodity category (e.g., cereals, vegetables), and food prices in ILS and USD.

2. **Political Violence Dataset (`palestine_political_events.xlsx`)**  
   - Contains monthly data on reported political violence events and fatalities.  
   - Event types include battles, violence against civilians, and explosions.

### Analysis Steps

1. **Data Inspection and Exploration**  
   - Load and inspect datasets for structure, missing values, and data consistency.  
   - Ensure price data has consistent units for accurate comparisons.

2. **Questions Addressed**  
   - When did food price monitoring begin in Gaza and the West Bank?  
   - What are the average prices for the `meat, fish, and eggs` category in Gaza versus the West Bank?  
   - Which commodities experienced the highest price volatility?  
   - How has the total number of fatalities varied across years?  
   - Do food prices correlate with violent events occurring in the same month?

3. **Data Visualization and Interpretation**  
   - Present insights through charts and statistical summaries.  
   - Derive meaningful interpretations from the results.

### Tools Used

- Python libraries for data analysis and visualization:
  - `pandas` for data manipulation.
  - `matplotlib` for visualization.
  - `numpy` for numerical computations.

## Results

The analysis highlights significant trends and relationships between violence and food prices, offering insights into how external factors affect economic stability in conflict regions.

