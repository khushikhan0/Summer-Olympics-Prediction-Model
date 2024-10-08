# README for Summer-Olympics-Prediction-Model

## Overview:  
This notebook contains analysis of Team USA Results for Female Gymnasts in the Olympic Games. Upon performing exploratory data analysis, we noticed that female athletes have won less overall medals than male athletes. We decided to delve into the performance of female athletes in the U.S. to determine if there are any systemic or historical reasons that have contributed to female athletes historically slightly “underperforming” in comparison to male athletes. Since the Olympics is an event marked by centuries of history, we predict that history may have shaped female athletes’ performances from the initial inclusion of women in the Olympics up to today. 

## Usage:
This file can be downloaded with Visual Studio Code or another compatible code editor. We used data from the athlete_events.csv file linked to this repository. Follow these steps to run this project locally: 
1. Clone the repository
   ```
    git clone https://github.com/khushikhan0/Summer-Olympics-Prediction-Model.git
   ```
3. Navigate to the project directory
   ```
   cd Summer-Olympics-Prediction-Model
   ```
5. Install the required dependencies [1] [2]
   ```
   download athlete_events.csv and total_gdp.csv
   ```

## Analysis: 
The notebook includes various steps such as:

1. Data Cleaning: Handling missing values, correcting data types, and filtering relevant records.
2. Exploratory Data Analysis (EDA): Visualizing the data to identify trends and patterns.
3. Historical Context: Investigating historical events that may have impacted female athletes' performances.
4. Modeling: Applying predictive models to forecast future performance trends.
   We decided to implement a K-Nearest Neighbors model, a Random Forest model, and a Support Vector Machine.

## Results: 
Our analysis revealed several insights into the performance of female athletes: 
1. Historical barriers and societal norms have impacted female athletes' opportunities and performances. We found that with the passage of laws such as Title IX in 1972, which provided girls in high school and college sports equal opportunity, there was a spike in the amount of female medal-earners [3]. Further, in 1991, non-discrimination on the basis of sex was added to the Olympic Charter [4]. This revived the upward trend of female medal-earners which initally began slowing down. From 2012 onward, female athletes began winning more medals than their male counterparts. 
2. Despite progress, female athletes still face challenges that can affect their medal counts compared to male athletes.
3. Predictive models suggest potential improvements in future performances as more support and resources are directed towards female athletes.

## Authors:
Saanvi Vutukur, Khushi Khan, Maya Sachidanand, and Serena Green

## References: 
[1] 120 years of Olympic history: athletes and results. (n.d.). Www.kaggle.com. https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-
             history-athletes-and-results/data <br />
[2] World Bank. (2023). GDP (current US$). The World Bank. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD <br />
[3] Minsberg, T. (2021, July 22). When Gender Equality at the Olympics Is Not So Equal. The New York Times. https://www.nytimes.com/2021/07/
             22/sports/olympics/olympics-athletes-gender.html <br />
[4] Women in the Olympic Movement. (2023). International Olympic Committee. https://stillmed.olympic.org/media/Document%20Library/
             OlympicOrg/Factsheets-Reference-Documents/Women-in-the-Olympic-Movement/Factsheet-Women-in-the-Olympic-
             Movement.pdf#_ga=2.196242796.1387851327.1545035637-2118090758.1543323217


