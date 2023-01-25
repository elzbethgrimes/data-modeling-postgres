# Sparkify Database

>The purpose of this database is to provide an easy way for Sparkify to look at and manipulate historical data they currently have in JSON files in order to answer business questions. 

## Database Schema

>Using a star schema will make reading and querying the data faster, providing simple data aggregation. It will work well for Sparkify because they are using historical data. The fact table, songplays, stores the quantitative information useful for analytical processes. Songs, artists, time, and users are the dimension tables. 
>
>An ETL pipeline provides an efficient way to grab, manipulate, and load the data into the necessary tables, allowing Sparkify to automate the process of bringing in data. 
>
>This database will help Sparkify to run queries and answer business questions. Such questions as: what kind of platform are most users using, where in the world are the majority of users logging in from, what percentage of users have a paid account, how long are users listening, and many other questions that will help Sparkify provide better service and attract more customers. 

## Running Python Files

>Run the python files using a terminal window. First, run the create_tables.py first. It will call the sql_queries.py file, which contains code to create Postgres tables and insert data into them. This file will also drop any of the tables if they have already been created to reset the tables. Next, use etl.pynb to run through steps that will aid in making the code for etl.py. After completing the steps in etl.ipynb go through test.ipynb until you reach the Sanity Check portion to test that the code created in etl.ipynb functions correctly. When the results on the first part of test.ipynb come back without any errors complete the code in etl.py. Then finish running the cells under the Sanity Check heading in the test.ipynb to ensure that the etl.py code is working correctly. 
>
>>-**create_tables.py** - displays the first few rows of each table to let you check your database.  
>>-**sql_queries.py** - contains all your sql queries  
>>-**etl.py** - reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook  
>>-**etl.ipynb** - reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.  
>>-**test.ipynb** - displays the first few rows of each table to let you check your database.  
>>-**README.md** - provides discussion on your project.  


