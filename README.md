# Unicorn_Companies_Analysis
# Cleaning and Analyzing data in Power query and Power BI
# Introduction
This is my first project while working at my previous job place. I analyzed a dataset from kaggle about unicorn companies around the world. A unicorn company, or unicorn startup, is a private company with a valuation of over $1 billion. As of June 2022, there are over 1,000 unicorns around the world. Popular former unicorns include Airbnb, Meta, and Google. Variants include a decacorn, valued at over $10 billion, and a hectocorn, valued at over $100 billion. The dataset contained 1037 unicorns and 10 columns which included information about company, valuation, date joined, country, city, industry, select founder, year founded, funding and financial stage.
# Data Cleaning
After importing my data into power query, I checked for duplicates(found none),the validity of my data using column distribution, quality and profiling and removed columns not neccessary for my analysis. I also made sure my columns were in the right data type.
# Data Preprocessing
file:///C:/Users/user/Desktop/Desktop/30%20days%20with%20Power%20BI/Completed%20Project/World%20Unicorn%20Company.pdf
I noticed the location column contained cities, states and countries so i split them using the "split by delimiter function"(since i needed the countries). In the newly created column, i discovered there were variations of spellings and USA was represented by its states. I cleaned this by adding a fuzzy cluster column in Power query and replacing the states with country. You can find the power query script
