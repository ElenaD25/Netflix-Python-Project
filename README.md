# Netflix
Data cleaning &amp; EDA

I created a Python project to analyze a Netflix dataset obtained from Kaggle. The goal was to perform data cleaning operations and conduct exploratory data analysis to gain insights into the content available on Netflix.

Project Steps:
1. Data Cleaning
 - Load the dataset into a Pandas DataFrame.
 - See the structure of the dataset using the info() command
 - Check for missing values and handle them appropriately (replace or remove)
 - Handle duplicates
 - Remove the "s" character from the show_id column
 - Split values and keep the first before the comma

2. Exploratory Data Analysis (EDA)
 - Explore the distribution of content types (movies vs. TV shows).
 - Analyze the distribution of content across different countries.
 - Investigate the distribution of release years and check for trends over time.
 - Analyze the distribution of ratings.
 - Explore the relationship between the duration of content and its type.
 - Examine the top 5 favored genre
 - Analyze the top 10 Movies/TV Show numbers per duration
 - Explore the most famous actors by the number of movies/shows they appeared in

3. Visualization 
 - Utilize libraries such as Matplotlib to create visualizations for key insights
 - Create a bar chart for the distribution of content types.
 - Plot a time series for the addition of content over the years
 - Create a pie chart to show the distribution of type content (movies vs TV Shows)
 - Horizontal bar chart for the top 10 countries based on the number of titles they produced
