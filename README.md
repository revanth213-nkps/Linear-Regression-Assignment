# Project Name
> Bike Sharing Demand Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project aims to analyze and predict bike-sharing demand based on various features such as season, weather conditions, and temperature.
- The project addresses the problem of understanding key factors influencing bike rentals and predicting future demand accurately.
- Dataset: The `day.csv` dataset contains daily bike-sharing data, including numerical and categorical variables like `temp`, `season`, and `cnt` (total count).

## Conclusions
- **Season and Weather Conditions**: Warmer seasons (`season_3` and `season_4`) and favorable weather (`weathersit_1`) lead to higher bike demand.
- **Temperature**: Bike rentals increase with higher temperatures (`temp` is strongly correlated with `cnt`).
- **Trend Over Time**: An increasing trend in demand is observed over the years (`yr`).
- **Model Performance**: The refined linear regression model achieved an R-squared score of 0.851 on the test dataset.

## Technologies Used
- Python - version 3.8+
- pandas - version 1.3.3
- numpy - version 1.21.2
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- scikit-learn - version 0.24.2
- statsmodels - version 0.12.2

## Acknowledgements
- This project was inspired by bike-sharing analysis case studies.
- Dataset provided as part of a machine learning exercise.
- Linear regression concepts referenced from [Statistical Learning Methods](https://www.statlearning.com).

## Contact
Created by Revanth
revanth.nkps@gmail.com
- Feel free to contact me if you need anything!

