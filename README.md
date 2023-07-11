# Sales Analysis Using Pandas

Set of real world data science tasks from Kaggle. 

Completed using the following Python libraries.
* import pandas as pd
* import matplotlib.pyplot as plt
* import os
* import re


##### Background Information

The above Python libraries were used to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.
The questions are listed below:
* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisements to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

##### Procedure
* We start by Merging 12 months of sales data into a single file.
* Proceeded by Cleaning our data. Tasks during this section include:
  1. Drop NaN values from DataFrame
  2. Removing rows based on a condition
  3. Change the type of columns (to_numeric, to_datetime, astype)
* Once we have cleaned up our data a bit, we move the data exploration section and analysis in answering te above business questions.

* To answer these questions we walk through many different pandas & matplotlib methods. They include:

  1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
  2. Adding columns 
  3. Parsing cells as strings to make new columns (.str)
  4. Using the .apply() method 
  5. Using groupby to perform aggregate analysis 
  6. Plotting bar charts and lines graphs to visualize our results 
  7. Labeling our graphs 
  
  