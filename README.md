# Nobel Prize Trends

The Nobel Prize is a famous scientific award. Every year, it's given to prestigous scientists in the following categories: Chemistry, literature, physics, physiology or medicine, economics, and peace. To win this prize, there are strict requirements and a very competitive environment to guarantee a full sense of objectivity.

Descriptive statistic is an amazing start point to obtain a general and wide panorama about some patterns.  

## Goal of the project
This project performs a Exploratory Data Analysis to discover some facts about Nobel Prize winners, specially to detect if there are some observable trends in Gender, Nationality and Age criteria.

## Getting Started
This notebook uses Python 3 and requires 3 additional libraries: pandas, seaborn, and matplotlib.

The dataset we use is provided by The Nobel Foundation and it's available on Kaggle: https://www.kaggle.com/nobelfoundation/nobel-laureates

## Road map
To accomplish our goal, the following steps are done:

- **EDA in Nationality variable**: Count unique winners (in case there were some winners that won several times) by nationality. 
- **EDA in Gender variable**: Verify distribution by gender and then observe how these distribution change over decades in different prize categories.
- **EDA in Age variable**: Perform a simple linear regression in Age winners over time to see if there are changes.
