![GWU cover](https://github.com/Abby7LIU/DNSC-6211-Programming-for-Business-Analytics/blob/master/GWU.png)
# ISTM-6212-Data-Management-for-Analytics
#### Learning Objectives (From Course Sllybus):     
- Develop theoretical foundation and practical experience working with a variety of traditional and contemporary data management tools, enabling you to work productively with any product or toolkit they might encounter
- Gain skill in wrangling and exploring data with a variety of tools inside and outside of databases
- Understand and be able to develop, deliver, and review reproducible data analyses

### Individual Assignments:
- [Exercise 1: Unix Shell Basics](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/G4420603_HW1.ipynb)         
Work through as much of the Software Carpentry lesson on the Unix Shell as you can. Run through the Setup section just below, then open a shell from the command line or with a terminal session through Jupyter to run through the exercises.
- [Exercise 2: SQL Queries Operations](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/A2_Abby(Jingyi)%20Liu.ipynb)          
Gain experience loading a CSV dataset into a database and using SQL to explore its contents. Write and execute a number of SQL queries using common syntax and functions.
- [Exercise 3: Trifacta Wrangler and Apache Spark](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/e3_G44206031.ipynb):     
Wrangle a data set using two new tools, Trifacta Wrangler and Apache Spark. Results should include a cleaned-up data set and summary statistics.
- [Exercise 4: Schema and SQL](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/assignment4-AbbyLiu.ipynb)    
Gain experience loading a CSV dataset into a star schema. Explore the data by writing and executing a number of SQL queries using common syntax and functions and describing your findings.
### Group Projects:
- [Project 1: Unix Shell Operations(Count, Filters and pipelines)](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/poject1_Abby.ipynb)    
- [Project 2: Build the shema and explore the dataset using SQL](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Project2.ipynb)
- [Project 3: Analysis on non-relational data(including its DataFrame and SQL interfaces) Using PySpark](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/project-3.ipynb)       

### Final Project: Chicago 2016 Taxi Rides Analysis 
![Project Cover](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Project%20Cover.png)
#### Codes and Details
- [CLean the data (Jupyter Notebook)](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Part1%20Clean%20the%20data.ipynb)
- [Wrangling and Analysis(Jupyter Notebook)](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Part1-Part4.ipynb)
- [Presentation Slide](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/ChicagoTaxislides.pdf)
#### Part 1 - Data Selection and Cleaning
Identify and describe your dataset, its source, and what appeals to you about it. Acquire the data and perform an initial exploration to determine which themes you wish to explore. Describe the questions you want to be able to answer with the data, any concerns you have about the data, and any challenges you expect to have to overcome.
#### Part 2 - Wrangling 
Based on what you found above, wrangle the data into a format suitable for analysis. This may involve cleaning, filtering, merging, and modeling steps, any and all of which are valid for this project. Describe your process as you proceed, and document any scripts, databases, or other models you develop. Be specific about any key decisions to modify or remove data, how you overcame any challenges, and all assumptions you make about the meaning of variables and their values.
![Schema](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Schema.png)
#### Part 3 - Analysis 
Explore and analyze your data in its wrangled form.  Follow through on the themes you identified in Part 1 with queries or scripts that answer the questions you had in mind.  Be clear about the answers you discover, discussing them and whether the results match your expectations.  Include charts or other visuals that support your analysis.  You may use Tableau, matplotlib, ggplot, or other tools we have not covered in class for visualization (and only for visualization), but be sure to export images from those tools and to include any images properly in your notebook writeup and slides.

__What we focus on:__
1. Which time does the customers use taxies most?
2. For the peak hours, what is do peopel's desitnation?
3. Which area is the most popular for people to use taxi?
4. How is the taxi priced, which company has highest initial charge?
5. Why some company have high initial charge?
6. Whcih ccompany has initial charge?
7. Why some companies have high tips?
8. Which payment type does people usually prefer?
9. What is trip total difference between weekends and weekdays?
10. What is the relationship between time and pickup location?
#### Part 4 - More data 
Sometimes the most value can be gained from one dataset when it is studied alongside data drawn from other sources.  Identify and describe at least one additional data source that can complement your analysis.  Pull this additional data into your chosen environment and explore at least one more theme you are able to further analyze that depends upon a combination of data from both sources.
In order to gain more information from the chicago taxi dataset, we was able to found another dataset which contains the weather of 30 countries in North America, from 2012 to 2017. To get what we want, we use csvcut to select `Chicago` column and then use xsv to select only 2016's data, save them into `chicago_weather_2016.csv`
