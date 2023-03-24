# Project 2: Crowdfunding, Extract Transform Load Pipeline

Arsam Ijaz and Ronald Lam, had proceeded to divide the work into the following parts:

Part 1: Arsam
Part 2: Ronald
Part 3: Arsam and Ronald
Part 4: Arsam and Ronald
Clean & stream line code: Ronald

## Part 1: Create the Category and Subcategory DataFrames
by Arsam

Using the crowdfunding.xlsx excel data located in the Resources directory, Arsam extracted and transformed the data creating two dataframes with unique 'id' columns linked to unique labels. Next he exported the dataframes as .csv files. 


## Part 2: Create the Campaign DataFrame
by Ronald

Using the crowdfunding.xlsx excel data located in the Resources directory, Ronald extracted the excel data to create a campaign dataframe. He extracted the column names and converted relevant columns to float and datetime data types. He then proceded to import the two .csv files in part one and merged them with the 'campaign' dataframe and exported to a .csv file. 


## Part 3: Create the Contacts DataFrame
by Arsam & Ronald

Arsam and Ronald imported and extracted the contacts.xlsx excel data in the Resources directory to create a dataframe. Using the for loop, .iterows, and json.loads function, along with list comprehension they iterated through the dataframe and appended each row to a list. With the list of lists, they created a usable dataframe with their respective column names. The name column was also split then dropped. Finally the dataframe was exported to a .csv file.


## Part 4: Create the Crowdfunding Database
by Arsam & Ronald

Arsam and Ronald referred to the four CSV files to create a Entity Relational Database of tables through QuickDBD. Using the database schema they created a Postgres database and imported the four CSV files to their SQL tables. 


## Conclusion
With SQL allowing to merge the four datasets and creating realationships among them, a user can reduce the time spent identifying the key elements of information that are needed to assess the data. The final portion of the project allows a user to consolidate the information and have a broader sight on what portions of the data are avaialble. This becomes crucial with larger datasets.
This code is expected to be improved over time, as proof, the "cleaning and streamlining the code" section of the project, was devoted to updating working code to be more efficient and easier read. This practice further develops code optimization that is applicable to similar and/or different datasets. This activity was a prime example of practicing efficiency. 
