# Capstone_Nss
# Capstone Project: Analyzing Obesity Prevalence and its Influencing Factors Across Countries

## Table of Contents
1. [Motivation](#Motivation)
2. [Questions](#Questions)
3. [Normalizing the Data](#normalizing-the-data)
4. [Problems and Hurdles](#problems-and-hurdles)
4. [Technologies](#Technologies)
5. [Data Sources](#data-sources)
6. [Conclusion](#conclusion)


# Motivation
Obesity has become a significant public health issue worldwide, with increasing rates observed in both developed and developing countries. This project aims to explore the factors contributing to obesity prevalence across countries over different time periods. By analyzing key indicators such as GDP per capita, daily protein supply, life expectancy, physical activity, meat consumption and population, this project provides insights into how socioeconomic factors influence obesity rates. These insights can help inform public health policies, promote healthier lifestyles, and ultimately improve public health outcomes.

# Questions
1. Which country had the greatest increase in obesity rates over time, and which had a decrease?  
2. Which country has the lowest obesity rates overall?
3. Was there difference in top five Obesity rates from 1990-2015? 
4. How does the distribution of obesity prevalence differ between 2000 and 2015?
5. Which five countries had the highest obesity rates in 2015? How do the obesity prevalence rates of the top five countries vary over time?
6. What are the Top five and Bottom five countries for each Year from 1990 to 2016?
7. How does obesity prevalence, compare across the years 1990, 2000, and 2010?
8. How does GDP per capita, compare across the years 1990, 2000, and 2010?
9. How does daily protein supply, compare across the years 1990, 2000, and 2010?
10. How does daily calorie supply, compare across the years 1990, 2000, and 2010?
11. How does population, compare across the years 1990, 2000, and 2010?
12. Is there any correlation between obesity prevalence and daily protein supply?
13. Is there any correlation between obesity prevalence and daily calories supply?
14. Is there any correlation between obesity prevalence and life expectancy?
15. How does obesity prevalence Correlate with socioeconomic factor like GDP per capita?
16. How does obesity prevalence Correlate with socioeconomic factor like population?
17. How Does meat consumption affect  Obesity prevalence?
18. How Does Average daily steps affect obesity prevalence?



# Normalizing the Data
 1.Handling missing data : Miising values are handled through .dropna method 
 2.Based on the main dataset i have included years starting from 1990 to 2016 only
 3.checked the data types, and changed the data types based on the priorities

# Problems and Hurdles
I was having trouble dowloading the data which has infomation about the deaths by Obesity prevalence, and also i had other data with information about the three countries i.e.,Peru, Mexico and Colombia. Thought of including this in my Analysis, but there are no matching Obesity Prevalence recorded for the main data set that i have, and ended up not working with that data.

# Technologies
1.Excel: Used for getting basic idea how the dataset looks after directly downloaded from the site
2.Pandas: For EDA, cleaning, Merging,Visualizations and trends 
3.Matplotlib and Seaborn: For generating static Visualizations such as bar charts, box plots, and sctater plots
4.Plotly: For creating intractive maps and complex visualizations
5.Jupyter Notebook: Used for documenting the analysis and presenting results
6.Numpy: For numerical calculations and statistical analysis
7.Tableau: For creating interactive dashboard
8.PowerPoint: For introduction of Project
9.Git: For version control and collaboration

# Imports
 `import pandas as pd`   
 `import numpy as np`  
 `import matplotlib.pyplot as plt`  
 `import seaborn as sns`
 `import plotly.express as px`

# Data Sources:
1. This project uses data from Our World in Data https://ourworldindata.org/
2. other datasets from Kaggle https://www.kaggle.com/ 
3. Includes information on various helath indicators
   Specific datasets are:
1. Obeisty prevalence by country
2. Gdp per capita by country
3. Daily protein intake per person
4. Daily calorie intake by person
5. Daily steps 
6. Life expectancy by country
7. Meat consumption
These datasets were collected over multiple years, allowing for longitudinal analysis from 1990 to 2016.

# Conclusion
This analysis provides valuable insights and the distribution of Obesity prevalence varies across countries with some countries had the greatest increase in obesity rates over time, and none of the countries had a decrease in Obesity rates over time. There are countries with lowest Obesity rates overall. The countries had higher 
Obesity rates in 2015 than compared to 1990. Since the Obesity rates are increasing over time. Considering Gdp per capita, daily protein supply, life expectancy, daily calories supply, there is moderate correlation between Gdp per capita and Obesity prevalence, the people in wealthier countries and more developed countries have more access to processed foods and sedentary lifestyles.The correlation between Average steps taken and obesity prevalence is surprisingly very weak, the physical activity alone may not be a predictor of Obesity. 





