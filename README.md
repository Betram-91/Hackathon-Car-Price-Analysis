# Dataset Content
Dataset contains 205 cars, including technical specifications and prices. 
Each row has a different car, and each column has features like engine size, horsepower, fuel type, and so on.

Some of the key columns are:

carname: brand and model
price: the car's price in USD
horsepower, enginesize, curbweight: these help describe performance
carbody, fueltype: Deisel/Petrol

I downloaded the dataset from Kaggle.

# Business Requirements
The goal is to help a car company understand:

- What features affect car prices
- Which car types are cheaper or more expensive
- Which brands give good value for money (performance vs. cost)

This can help the company make better decisions about pricing and design.

As a student, I am using this project to practice data cleaning and finding answers to simple questions using Python, Pandas, and NumPy.

# Hypothesis and how to validate?
Here are some ideas (hypotheses) I want to test in this project:

1. To analyse the average car prices per name to understand pricing variations across different brands
2. To visualising relationships between car attributes and car price
3. To use simple regression model to estimate car prices based on key attributes


# Project Plan
I followed this plan:

1. ETL: Extract, Transform, Load

Loaded the dataset
Cleaned column names and values
Removed outliers if there were any
Created new columns (carbrand, price_per_hp)
Saved cleaned data

2. Data Analysis

Grouped data by brand, car body, fuel type

Calculated average prices and MPG

3. Visualisations:

Created charts using Matplotlib, Seaborn, and Plotly

4. Documentation:

Wrote this README and added comments to my notebook

# The rationale to map the business requirements to the Data Visualisations

Business Question and Visualisation Used:
Which brands are most expensive?	Bar chart (avg. price by brand)
Which brands give best value?	Bar chart (price per horsepower)
Does car type affect price/efficiency?	Bar charts (city MPG & price by carbody)
Does more power = higher price?	Scatter plot (horsepower vs price)

# Analysis techniques used
Used .groupby() and .mean() to compare brands and car types
Created new columns like price_per_hp and power_to_weight

Visualised results with:
Matplotlib (basic plots)
Seaborn (grouped bar charts)
Plotly (interactive scatter plots)

# Ethical considerations
The data is public and contains no personal information
This project was done for learning purposes only

# Unfixed Bugs
Some Matplotlib and Seaborn plots saved as blank images in VSCode
Fixed this by switching to Plotly or using fig.savefig() correctly

# Development Roadmap
If I continue this project, I would like to:

Add more data like car mileage and car year

# Main Data Analysis Libraries
Pandas – for loading, cleaning, and analysing the data
NumPy – for basic math and logic
Matplotlib – for basic plots
Seaborn – for nicer grouped charts
Plotly – for interactive plots

# Credits
Dataset: Kaggle - Car Price Prediction
Help: Project supported by classgroup, ChatGPT and Microsoft COpilot

