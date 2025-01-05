# Sprint_5_Video_Game_Forecast
### Video Game Sales Forecast
___
##### Introduction:<br>
The goal of this project is to uncover advertising strategies for a global video game retailer. We have historical video game sales data for many platforms and areas of the world.

In this notebook we will load and explore the data developing a plan of action to prepare this data for exploration. Preparation will begin in the preprocessing.ipynb :<br>

Preprocessing the data will consist of cleaning the data inorder to ensure data is accurate and consistent. Techniques involved are:

Removing duplicate entries, both complete and partial duplicates for columns that should have unique combinations

Filling Missing Values: Missing data points will be examined, and filled as needed. Most of the missing values were in critic/user ratings. These values were left empty. Some other missing values had their own values not the typical Nan, Null, None values

Standardizing Values: Data entries may have different spelling or formats from eachother while meaning to express the same value. 

Feature Engineering: Creation of new data columns that might be useful, total_sales, mobile, brand etc.

Once Pre processing is complete the data will be stored as preprocessed_games.csv

##### EDA: EDA.ipynb <br>
Now that our data has been prepared in the preprocessing notebook, we will continue toward the goal of making global video game advertising suggestions.

In this notebook the processed data will be explored, and then some analysis will be conducted. 

Topics explored:
- How has video game production changed over time?
- Determine the relevant time period for available data
- How long are platform lifespans?
- Look at sales over time
- What are the popular platforms, genres, ratings
- Are trends different in different regions?
- Do critic reviews matter?
- Are differences in sales means statistically significant? Can differences be referred to as chance?

#### Insights & conclusions
___
There are some differences between purchasing habits in different markets. Japan favors role-playing or action genres, are more open to mobile gaming platforms, less interested in mature rated games.

Europe and North America are more aligned. Both favoring action and shooter genres, non-mobile platforms, and mature rated games. Europe prefers racing games more than North America. 

Platforms have an average lifespan (timeline of game production) of 7 years, and game production sharply declines right before being replaced.

### Tools
___
Tools being used during the analysis are:

Pandas: <br>
Library with tools used for data manipulation and analysis. All tables being displayed are in the pandas dataframe format. This is the primary tool used for cleaning, transforming, and aggregating the dataset.

Plotly Express:<br>
A data visualization library used to create interactive plots and visualizations.

SciPy Stats:<br>
A powerful tool for statistical analysis. We will be using levene and ttest's during analysis

GitHub:<br>
A web-based platform that allows users to store, share, and manage code. Github is also a service that facilitates version control, allowing multiple contributers to make changes, while offering the means to correct potential mistakes.

VScode:<br>
IDE or coding platform used to in creation of this project.
