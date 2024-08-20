# Data Science Project
Set of real world data science tasks completed using the Python Pandas library.

## Setup

To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html 

## Background Information:

In this project, I utilise Python Pandas and Python Matplotlib to analyse and answer business questions based on 12 months of sales data. The data includes hundreds of thousands of electronics store purchases broken out by month, product kind, price, purchase address, and so on. 

I start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up our data a bit, I move the data exploration section. In this section I explore 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should I display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

