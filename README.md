# SpaceX-Falcon9-First-Stage-Landing-Prediction

**IBM Data Science Capstone Project**

## Introduction

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)

In this capstone project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. With the help of the data science findings and models, the competing startup can make more informed bids against SpaceX for a rocket launch.

Assuming the role of a data scientist of a startup rivaling SpaceX, the goal of this project is to create a machine learning pipeline to predict the landing outcome of the first stage in the future; and in the process leading upto the final goal, we follow the data science methodology involving data collection, data wrangling, exploratory data analysis, data visualization, model development and model evaluation.

## Table of Contents
1) [**Data Collection with API**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/02-Data-Collection/DataCollection_API.ipynb)
2) [**Data Collection with Web Scraping**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/02-Data-Collection/DataCollection_WebScraping.ipynb)
3) [**Data Wrangling**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/03-Data-Wrangling/DataWrangling.ipynb)
4) [**EDA with Visualization**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/04-Exploratory-Data-Analysis/EDA_DataVisualization.ipynb)
5) [**EDA with SQL**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/04-Exploratory-Data-Analysis/EDA_SQL.ipynb)
6) [**Interactive Visual Analytics with Folium**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/05-Interactive-Data-Analytics/InteractiveDataAnalytics_Folium.ipynb)
7) [**Predictive Analysis - Machine Learning**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/06-Predictive-Analysis/PredictiveAnalysis_MachineLearning.ipynb)

## Executive Summary
The analysis aims to identify the factors for a successful rocket landing. To make this determination, the following methodologies were used:
- Collect data using SpaceX REST API and web scraping techniques
- Wrangle data to create success/fail outcome variable
- Explore data with data visualization techniques, considering the following factors: payload, launch site, flight number and yearly trend
- Analyze the data with SQL, calculating the following statistics: total payload, payload range for successful launches, and total number of successful and failed outcomes
- Explore launch site success rates and proximity to geographical markers
- Visualize the launch sites with the most success and successful payload ranges
- Build Models to predict landing outcomes using K-nearest neighbour (KNN), decision tree, support vector machine and logistic regression.

## Getting Started
If you're new to this repository or data science in general, here's how you can get started:

1. Clone the repository to your local machine using `git clone https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction`.
2. Navigate to the project you're interested in within the repository.
3. Run, and explore the code.

## Contributing
Contributions are most welcome! If you want to contribute, make sure to go through [**CONTRIBUTING.md**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/CONTRIBUTING.md). Any improvements, bug fixes, or additional projects are greatly appreciated.

## License
This project is licensed under the [**MIT License**](https://github.com/shashankarya9999/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/main/LICENSE). You are free to use the code and resources for educational or personal purposes with citation or reference to the original code and resources used.

## Contact
I welcome any feedback, discussion, suggestion or question regarding any of the projects or any kind of sponsorships for the repository. Feel free to reach out to me via email at shashankarya9831@gmail.com

###### © Copyright IBM Corporation 
###### Copyright (c) 2024 Shashank Arya
