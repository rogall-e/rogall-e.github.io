---
title: "Kings County Data Set Project"
date: 2020-06-13
tags: [data science life circle, data science, EDA, Pandas , NumPy , Matplotlib , Seaborn , Plotly , math , statsmodels , sklearn]
header:
  image: "/images/2020-06-13-Project_Kind_County_Houses_Eike_files/city-skyline-693502_1280.jpg"
  teaser: "https://cdn.pixabay.com/photo/2015/03/26/22/09/city-skyline-693502_1280.jpg"
excerpt: "Data Science Life Circle, Data Science"
mathjax: "true"
---
# EDA-Project-NeueFische

This project is still **in progress**


## Overview

This project is about predicting house prices in the area of Seattle/King County based on the Kings County Dataset. The Dataset contains 21 variables of 21597 houses. The project was part of a data science bootcamp and should cover all stages of the data science cycle:

## Data Science Lifecycle

- 1 Business Understanding
- 2 Data Mining
- 3 Data Cleaning
- 4 Data Exploration
- 5 Feature Engineering
- 6 Predictive Modeling
- 7 Data Visualization


## Python Modules used:
Pandas / NumPy / Matplotlib / Seaborn / Plotly / math / statsmodels / sklearn

[Jupyter Notebook](https://github.com/rogall-e/EDA-Project-NeueFische/blob/master/Project_Kind_County_Houses_Eike.ipynb) <br>
[Short presentation about the results of this project](https://github.com/rogall-e/EDA-Project-NeueFische/blob/master/EDA-KingsCounty.pdf)



# Introduction
My goal in this project was to create a model that can predict the house prices based on the Kings County Data Set for different target groups.
The first group I wanted to find a house for was a family of four. So i aseked myself the questions: How expensive is a house for a standard four person house hold? Are there any bargains and where is the cheapest house with the optimal features?
My second thought was can I find a good investment opportunity with the same model? So i looked for cheap houses in a bad condition, that haven't been reovated.



# Conclusion
Based on my initial questions I found two houses for a family of four. One on the Outskirts for 265,000.00 US-D	2,920 square footage of living space and 5,250 squre footage of land space within the best conition. But I also looked for a house in the urban area of Seattle and found one for 290,000.00 US-D with 2,240 squre footage of living space and additional 8,162 squre footage of land space.
For the investment opportunity I found based on the prediction of my model 6 houses, that were identified as potential investments. Additionally I compared the price of the house with the average house price of a defined area. The most lucrative house would cost 335,000 $ and is roughly 108,000 $ cheaper than the average house price in the area (9 houses located in the area).

# Outlook
There should be done further optimisation of the Linear Regression Model. A R&sup2; of 74.5 % is good but could still be improved. Furthermore testing if other ML models lead to better results should be carried out.
