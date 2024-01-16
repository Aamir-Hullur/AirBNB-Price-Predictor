# NYC-Airbnb-EDA-Price-Prediction

## Project Overview
This repository hosts a comprehensive project aimed at analyzing and predicting Airbnb prices in New York City. Central to this project is an extensive Exploratory Data Analysis (EDA), where we delve into the intricate relationships between different features of over 100,000 Airbnb listings. Our project is a blend of detailed data visualization and advanced predictive modeling.

## Technologies Used
- Python
- Jupyter Notebook
- Machine Learning Algorithms:
  - Linear Regression
  - Decision Trees
  - Random Forest Regression
  - Support Vector Regression (SVR)
  - XGBoost

## Key Highlights
- Extensive EDA to explore and visualize the Airbnb market dynamics in NYC.
- Analysis of key features influencing Airbnb pricing using data visualization tools.
- Comparative performance analysis of various predictive models.
- Insights into the geographical distribution of prices and room type influences on pricing.

## Exploratory Data Analysis (EDA) Highlights
Below are some highlights from our extensive exploratory data analysis:

One key aspect of our EDA was analyzing the distribution of listings among different hosts in NYC. The following bar chart represents the number of listings each host has:

![Number of Listings per Host](/images/number_of_listings_per_host.png)
*Figure: Number of Listings per Host - This visualization helps to understand host distribution and listing frequency in the Airbnb NYC dataset.*


We also conducted a textual analysis of the 'neighbourhood' column in our dataset. The word cloud below illustrates the most frequently mentioned neighbourhoods in Airbnb listings:

![Neighbourhood Word Cloud](/images/neighbourhood_word_cloud.png)
*Figure: Word cloud visualization representing the frequency of neighbourhood mentions in NYC Airbnb listings.*


Our dataset analysis includes a breakdown of the types of rooms available in Airbnb listings. The pie chart below shows the proportion of each room type:

![Room Types Distribution](/images/room_types_distribution.png)
*Figure: Pie chart depicting the distribution of room types in NYC Airbnb listings.*

## Outlier Detection Analysis
An important part of our EDA was identifying outliers within the dataset. The box plot visualizations below illustrate the outliers across different features:

![Outlier Identification Box Plot](/images/outlier_identification.png)
*Figure: Box plots for outlier detection in various features of the NYC Airbnb dataset, excluding 'host_id' and 'id'.*

## Model Performance Comparison
The following table showcases the performance metrics of the various models we tested:

![Model Performance Comparison](/images/model_comparison.png)
*Table 1: Comparison of model performance metrics*

## Authors
- Aamir Hullur
- Parth Godse

## Acknowledgements
- Dataset sourced from Kaggle

