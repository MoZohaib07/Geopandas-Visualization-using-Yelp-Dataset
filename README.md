Yelp Dataset Analysis

This project involves analyzing the Yelp dataset to explore business reviews across different states in the US. The analysis includes data cleaning, statistical analysis, and visualization using various Python libraries. Key features include the correlation between reviews and ratings, and visualizing business data on a map of the US. I have attached the files I used for Geopandas visualization on the United States Map.

Data Source
The dataset used for this analysis is the Yelp Academic Dataset, which includes business information such as review counts, ratings, and location data.

Key Functions and Features
Data Cleaning: Removing unnecessary columns for a focused analysis.
Statistical Analysis: Examining the correlation between the number of reviews and average ratings.
Data Aggregation: Grouping data by state to compute total businesses, total reviews, and average ratings.
Visualizations:
Bar graph of total reviews per state.
Heatmap of the number of businesses by state.
Heatmap of average ratings by state.
Scatter plot of total businesses vs. total reviews with a line of best fit.
Geospatial Analysis: Using GeoPandas to visualize business data on a US map.

Requirements
Python 3.x
pandas
numpy
matplotlib
seaborn
geopandas
statsmodels

Usage
Install the required libraries:
pip install pandas numpy matplotlib seaborn geopandas statsmodels
Run the Jupyter Notebook to perform the analysis and generate the visualizations.
