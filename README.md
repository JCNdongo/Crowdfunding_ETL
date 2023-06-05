# Crowdfunding_ETL: A collaboration by Daniela Perez-Macias & Jean-Claude Ndongo
ETL mini project: working with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform data.

This project was based on extracting, transforming, and loading (ETL) data using .xlx, .csv and json files and pandas functions.  First, we extracted the Crowdfunding.xlsx file from the resources file and transformed it into a pandas DataFrame. 

We began the data transformation stage by converting the categories columns and data rows from the file into corresponding keys and values in pandas using a loop function. Next, we split the categories and sub-categories keys and corresponding values into separate entities in preparation of our data analysis. We created a new DataFrame (campaign_df) based on the initial file and added a column for unique identifier IDs for each data point matched with a .csv file (contact.csv) containing contact information for each row. 

As part of our data cleaning process, we converted values associated with monetary figures from an integer to float format, and dates to the appropriate format using the datetime pandas function. We also removed columns that were unnecessary to our analysis. 

We resumed cleaning as we imported the aforementioned .csv file with contact information into pandas and created a DataFrame using a json.loads looping function to import the file’s content (ID, names, and email addresses). We transformed the data in the new DataFrame by splitting first names from last names and reorganizing the columns’ order. 

Lastly, we loaded the file into a .csv file which constituted a cleaner version of the contact.csv file. With this project, we practiced the extracting, transforming, and loading (ETL) skills necessary for adequate data analysis. 
