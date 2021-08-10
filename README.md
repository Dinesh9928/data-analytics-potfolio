# Data-analytics-potfolio

Repository containing portfolio of data analytics projects completed by me for academic, self learning, 
and hobby purposes. Presented in the form of iPython Notebooks,



# Contents
* ### Data Analytics 
### <a href="https://github.com/Dinesh9928/data-analytics-potfolio/blob/master/Project%20On%20IDBM_Movie_Data.ipynb">IDBM Movie Ratings Data Analysis</a>: The aim of the project is to analyze the IDBM_Movie_Data
*  1. Load the data into your working area and get the information about the null values.
*  2. Rename the columns for the analysis purpose if any columns are not in proper way
*  3. Handle the missing value columns with the proper assumtion.
*  4. Generate the relationship between each continuous variable using corr() method.
*  5. Find the movies directed by 'James Gunn', & 'Ridley Scott' with the rating greater than or equal to 8.
*  6. Display all the movies directed by 'Ridley Scott'.
*  7. Display all the director's who got the rating >= 8 for their movies.
*  8. Find all the movies directed by 'James Gunn', & 'Ridley Scott'.
*  9. Display all the movies with the ratings between 8 & 9 and also the films with the highest rating.
*  10. Find the movies directed by both 'Christopher Nolan' and 'Ridley Scott'
*  11. Find all movies that were released between 2006 and 2010, have a rating above 8.0, but made below the 50th percentile in revenue.
*  12. Find all movies that were released between 2006 and 2010, have a rating above 8.0, but made below the 25th percentile in revenue.
*  13. Finally give the feedback for all movies with 'Good' if the movie 'rating' is >= 8 and 'Average' if the movie rating doesn't follow the condition given.
   The Dataset Consist of 1000 Rows and 11 Columns. 
   
   
 ### <a href="https://github.com/Dinesh9928/data-analytics-potfolio/blob/master/Project_Analytics%20On%20Global%20Superstore%20Data%202016.ipynb">Project_Analytics On Global Superstore Data 2016</a>: The aim of this project is to analyse the data with respect to the sales and profit after filtering some of the columns.
The data 'global_superstore_2016' consists of 51290 entries (that is rows) and total 24 columns. The columns Order Date & Ship Date are not in one specific format and also in Datetime type,our job is to convert these columns to the Datetime objects first.
And in the second stage, the columns 'Sales' and 'Profit' consist of special symbols like [ '$',"(", and ")"]
so will filter these columns and convert them into an either int or float type. After converting these columns into an int or float type remove the columns which are not necessary with respect the data analysis. After doing this cleaning process, we will analyse the data with respect to the following objectives.
 ### Objective
 * Find Total, how many orders have cross the shipping cost of 500.
 * Count the number of segments, countries, regions, markets, categories, and sub-categories present in the global_superstore_2016 data.
 * Get the list of Order ID's where the Indian customer's have bought the things under the category 'Technology' after paying the Shipping Cost more than 500.
 * Get the list of Order ID's where the Indian customer's have bought the things under the category 'Technology' the Sales greater than 500.
 * Find How many people from the State 'Karnataka' have bought the things under the category 'Technology'
 * Get the list of countries where the 'Profit' and 'Shipping Cost's are greater than or equal to 2000 and 300 respectively.
 * Find the list of Indian states where the people have purchased the things under the category Technology.
 * Find the overall rank of "India" where the 'Profit' is maximum under the category 'Technology'.
 * Display the data with min, max, average and std of 'Profit' & 'Sales' for each Sub-Category under each Category

  ### <a href="https://github.com/Dinesh9928/data-analytics-potfolio/blob/master/Project%20On%20Olympics_Data.ipynb">Project On Olympics_Data</a>: Aim of this project for the Olympics data is to analyze with the following details:
 ##### Project Objectives:
* Find In which events did Edwin Flack win a medal?
* Which country has won the most men's gold medals in Athletics over the years? Sort the results alphabetically by the player's names.
* How many gold medals the Indian Men's have won and name the event also?
* Check to see how many Indian women's have won the gold, silver or branze medals in the Olympic games?
* Which five countries have won the most medals in recent years (from 2000 to 2008)?
* Display the male gold medal winners for the hockey event over the years. List the results starting with the most recent. Show the Olympic City, Edition, Athlete and the country they represent.
* How many women's have won the gold medal's till 2008 in Olympic game?
  
  <i>Tools: scikit-learn, Pandas, Seaborn, Matplotlib</i>
