# SpaceX-Falcon9-First-Stage-Landing-Prediction

**IBM Data Science Capstone Project**

## Introduction

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)

In this capstone project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. With the help of the data science findings and models, the competing startup can make more informed bids against SpaceX for a rocket launch.

Assuming the role of a data scientist of a startup rivaling SpaceX, the goal of this project is to create a machine learning pipeline to predict the landing outcome of the first stage in the future; and in the process leading upto the final goal, we follow the Data Science methodology involving data collection, data wrangling, exploratory data analysis, data visualization, model development and model evaluation.

## Explore
- How payload mass, launch site, number of flights, and orbits affect first-stage landing success
- Rate of successful landings over time
- Best predictive model for successful landing (binary classification)

## Executive Summary
The analysis aims to identify the factors for a successful rocket landing. To make this determination, the following methodologies were used:
- Collect data using SpaceX REST API and web scraping techniques
- Wrangle data to create success/fail outcome variable
- Explore data with data visualization techniques, considering the following factors: payload, launch site, flight number and yearly trend
- Analyze the data with SQL, calculating the following statistics: total payload, payload range for successful launches, and total number of successful and failed outcomes
- Explore launch site success rates and proximity to geographical markers
- Visualize the launch sites with the most success and successful payload ranges
- Build Models to predict landing outcomes using K-nearest neighbour (KNN), decision tree, support vector machine and logistic regression.
  
## Table of Contents

1) [**Data Collection with API**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/DataCollection_API.ipynb)
2) [**Data Collection with Web Scraping**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/DataCollection_WebScraping.ipynb)
3) [**Data Wrangling**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/DataWrangling.ipynb)
4) [**EDA with Visualization**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/EDA_DataVisualization.ipynb)
5) [**EDA with SQL**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/EDA_SQL.ipynb)
6) [**Interactive Visual Analytics with Folium**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/InteractiveDataAnalytics_Folium.ipynb)
7) [**Predictive Analysis - Machine Learning**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/PredictiveAnalysis_MachineLearning.ipynb)

##### Acknowledgements
###### © Copyright IBM Corporation 
###### Copyright (c) 2024 Shashank Arya


