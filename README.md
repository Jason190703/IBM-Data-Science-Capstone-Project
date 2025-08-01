# Stock & Revenue Trend Analysis: A Business Intelligence Capstone Using Real-World Financial Data
This project was completed as part of the IBM Data Science Professional Certificate Capstone on Coursera. It applies the full end-to-end data science process to analyze the relationship between a company’s stock prices and quarterly revenue over time.

The main goals include:
    -  Analyze trends between stock prices and company revenue
    -  Explore temporal patterns (e.g., events, seasons) affecting performance
    -  Build simple models to classify stock movement based on revenue
    -  Use interactive visualizations for business insights
    -  Compare financial behavior across companies and sectors (e.g., Tesla vs. Walmart)


# Project Background
  This project explores the relationship between historical stock prices and company revenue over time. Using real-world data from companies like Tesla and Walmart, we investigate how internal financial metrics (like revenue) correlate with external market behavior (stock prices).
  The project is part of the IBM Data Science Professional Certificate Capstone and applies the full data science workflow: data collection, wrangling, exploratory analysis, visualization, and predictive modeling.
  
# Questions to be answerd
  1. How does a company’s revenue relate to its stock performance over time?
  2. Are there observable trends or patterns in stock or revenue data that align with specific time periods (e.g., holidays, product launches, economic events)?
  3. Can we build a model that predicts stock movement based on revenue data?
  4. What business insights can be derived from visualizing stock and revenue data interactively?
  5. Do different sectors (e.g., tech vs. retail) behave differently in terms of stock-revenue alignment?

# Methodology
  1. Data Collection:
     Stock data via Yahoo Finance (yfinance API)
     Revenue data from MacroTrends (web scraping)
     
  2. Data Wrangling:
     Cleaned null values
     Standardized date formats
     Merged datasets on quarter/year
     
  3. Exploratory Data Analysis (EDA):
     Visualized stock vs. revenue
     Checked distributions, outliers, correlations

 4. SQL Analysis:
     Queried revenue and stock data using IBM Db2
     Filtered high/low performing quarters

  5. Interactive Visualization:
     Created dashboards using Plotly Dash
     Built maps with Folium for spatial insights

 6. Predictive Modeling:
    Applied logistic regression for classification
    Evaluated performance using accuracy, confusion matrix, F1 score
