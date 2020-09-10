# Zomato Restaurants Reviews #

Group project:
- Ashley Drayton
- Babette Blanquet 
- Benedict Nathaniel 
- Erica Wearne

In this group project, our goal is to understand how Melbourne's restaurants are valued compare to Australians' restaurants.

## Hypothesis, questions and overall findings: ##

**Our hypothesis are:**
- Melbourne is the cultural epicentre of Australia and renowned for the quality and diversity of its food.
- Melbourne has the best restaurants amongst the five largest cities in Australia.

**Question:**
Does Melbourne really have the best restaurants in Australia based on price, ratings and diversity of cuisines?

**Key findings:**
Melbourne has the highest rated restaurants however it comes at a higher price.

## The Data Exploration and The Data Clean-up ##

The code for the data exploration and data cleaning in the Jupyter Notebook named: "Zomato_data_exploration_and_cleaning_"

**Data Sources**
- We used Zomato API to gather the data
- Our dataset included 500 restaurants which is the combination of the Top 100 restaurants of Melbourne, Sydney, Brisbane, Adelaide, Perth
**Challenges**
- We wanted 1000 restaurants per city but the limitation of 100 restaurants maximum per call.
- Even though we could get around this constraint by searching for multiple postcodes, we worked with the central postcodes due to time contraints.
**Biases**
- By choosing only the five cities, this excluded possibly excellent restaurants in rural areas of Australia butwe were interested in the best restaurants where most Australians live.

**The Data Clean-up**
- The data is saved to a .csv
- we removed the duplicates with .dropna()
- removed incorrect cells by sorting the data, then removing incorrect values
- sorted the data by user ratings to extract the top 100 restaurants in Australia

## The Data Analysis ##

The code with the data analysis is in the Jupyer Notebook named: "Zomato_Restaurants_Analysis"

**Restaurant Distribution and Average User Rating**

- 44% of the Top 100 Restaurants are in Melbourne.

![Distribution Top 100](Final_notebooks/images/DistributionTop100.png)

- When we look at the Top 500 restaurants, Melbourne is just ahead on average user ratings than Sydney.

![Average User Ratings](Final_notebooks/images/AvUserRating500.png)

**User ratings across top 500 restaurants in each city**
- Melbourne and Sydney have a slightly higher ratings than other cities among their Top 100 restaurants.
- This makes sense has they also are much bigger cities than the others.
![Distribution User Ratings](Final_notebooks/images/UserRatingperCity.png)



















--------------------------------------------------------------------------
Please see our project in the folder named 'Final notebooks'.
You will find 
- two notebooks, one for the Data Exploration and Data Cleaning and one for the Data Analysis
- the folder with "outputdata" with csv files
- the folder with "images"  where we saved the graphs of our analysis
- the PowerPoint presentation

Thank you.
#Teal Rabbits Team
