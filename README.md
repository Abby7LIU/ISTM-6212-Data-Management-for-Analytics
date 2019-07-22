![GWU cover](https://github.com/Abby7LIU/DNSC-6211-Programming-for-Business-Analytics/blob/master/GWU.png)
# ISTM-6212-Data-Management-for-Analytics
## Individual Project:
#### [3. Exercise 3:  Wrangle a dataset using Trifacta Wrangler and Apache Spark. R](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/e3_G44206031.ipynb)
__Part 1:__ Select a CSV dataset from the OKFN US City Open Data Census. Choose one according to your interest, but try to choose one that's "green" and has somewhere between 10,000 and 1,000,000 rows. Try also to choose a dataset that is less than 50MB (to save us some time and space during grading!).        
__Part 2:__ Use Spark to load your data and compute basic summary statistics (counts, or average, min/max, and mean). You may borrow liberally from the example we saw in class, just change a few things as appropriate.

## Final Project: Chicago 2016 Taxi Rides Analysis 
![Project Cover](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Project%20Cover.png)
### Codes and Details
#### 1. [CLean the data (Jupyter Notebook)](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Part1%20Clean%20the%20data.ipynb)
#### 2. [Wrangling and Analysis(Jupyter Notebook)](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Part1-Part4.ipynb)
#### 3. [Presentation Slide](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/ChicagoTaxislides.pdf)
### Part 1 - Data Selection and Cleaning
Identify and describe your dataset, its source, and what appeals to you about it. Acquire the data and perform an initial exploration to determine which themes you wish to explore. Describe the questions you want to be able to answer with the data, any concerns you have about the data, and any challenges you expect to have to overcome.
### Part 2 - Wrangling (35 points)
Based on what you found above, wrangle the data into a format suitable for analysis. This may involve cleaning, filtering, merging, and modeling steps, any and all of which are valid for this project. Describe your process as you proceed, and document any scripts, databases, or other models you develop. Be specific about any key decisions to modify or remove data, how you overcame any challenges, and all assumptions you make about the meaning of variables and their values.
![Schema](https://github.com/Abby7LIU/ISTM-6212-Data-Management-for-Analytics/blob/master/Schema.png)
### Part 3 - Analysis (35 points)
Explore and analyze your data in its wrangled form.  Follow through on the themes you identified in Part 1 with queries or scripts that answer the questions you had in mind.  Be clear about the answers you discover, discussing them and whether the results match your expectations.  Include charts or other visuals that support your analysis.  You may use Tableau, matplotlib, ggplot, or other tools we have not covered in class for visualization (and only for visualization), but be sure to export images from those tools and to include any images properly in your notebook writeup and slides.
#### What we focus on:
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

### Part 4 - More data (10 points)

Sometimes the most value can be gained from one dataset when it is studied alongside data drawn from other sources.  Identify and describe at least one additional data source that can complement your analysis.  Pull this additional data into your chosen environment and explore at least one more theme you are able to further analyze that depends upon a combination of data from both sources.

In order to gain more information from the chicago taxi dataset, we was able to found another dataset which contains the weather of 30 countries in North America, from 2012 to 2017. To get what we want, we use csvcut to select `Chicago` column and then use xsv to select only 2016's data, save them into `chicago_weather_2016.csv`
