# CDAC_Project
# Analysing and Visualising Trends of Global Warming and Predicting 2°C breach (from Pre-Industrial Temperatures) based on GHG
![concept-illustration-global-warming-around-the-royalty-free-image-1707420637](https://github.com/user-attachments/assets/cca6f018-cece-48b0-8ce7-ecb2895bc0c3)
Under the Paris Agreement adopted in 2015, virtually all the world’s nations pledged to limit global warming to “well below” 2C above pre-industrial levels and also, if possible, “pursue” efforts to cap warming at 1.5C. At present, the world is not close to being on track to meet either target. 

# What we are solving
This project focuses on predicting the year when global temperatures will breach the 2°C threshold above pre-industrial levels, a critical milestone under the Paris Agreement. The project utilizes historical temperature data and greenhouse gas emissions (nitrous oxide, methane, and CO₂) to forecast future temperature anomalies.

## What does the studies say
 - The world will likely exceed 1.5C between 2026 and 2042 in scenarios where emissions are not rapidly reduced, with a central estimate of between 2030 and 2032. 
 - The 2C threshold will likely be exceeded between 2034 and 2052 in the highest emissions scenario, with a median year of 2043. 
 - In a scenario of modest mitigation – where emissions remain close to current levels – the 2C threshold would be exceeded between 2038 and 2072, with a median of 2052.

### Dataset
The dataset includes yearly average temperatures by country, along with associated greenhouse gas emissions:

 - Country: The name of the country.
 - Year: The year of recorded data.
 - Average Temperature: The country's yearly average temperature.
 - Annual Nitrous Oxide Emissions: In CO₂ equivalents.
 - Annual Methane Emissions: In CO₂ equivalents.
 - Annual CO₂ Emissions: Direct CO₂ emissions.

## Methodology
### Data Preprocessing:

Handling missing values.
Feature selection, focusing on key emission variables and temperature data.

### Modeling:

Several machine learning models were applied to predict the year of the 2°C breach, including:
Linear Regression
Random Forest
XGBoost
Each model was evaluated for accuracy, and predictions were made based on the best-performing model.

### Analysis:

Tableau was used to visualize temperature trends and emission data across different countries and years, uncovering critical insights into global warming patterns.

### Interactive UI:

A Flask-based web application was developed to present the findings interactively. Users can input data, view predictions, and explore Tableau visualizations directly from the application.

## Results
The models predict the year when the global temperature is expected to breach the 2°C threshold, offering critical insights into future climate change scenarios. The combination of machine learning and visual analytics provides a comprehensive tool for understanding and addressing global warming.

