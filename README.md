# Movies-ETL
In this project we help Britta to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
We need to refactor the code from module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
Britta needs all that data to be prepared for the hackathon. She needs to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, clean dataset to use.
To do this, we followed the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.
The idea behind ETL is straightforward. Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. ETL breaks this problem into three steps, or phases: Extract, Transform, and Load.
For Britta, we extracted scraped Wikipedia data stored as a JSON, and Kaggle data stored in CSVs.
The goal to create a consistent structure in the data was achieved. Without a consistent structure in our data, it's almost impossible to perform any meaningful analysis.

Python and Pandas are especially good for prototyping an ETL transformation because they provide flexibility and interactivity (especially in a Jupyter Notebook), without enforcing any complicated frameworks.cument, and perform our data transformation.
Finally, after the data is transformed into a consistent structure, it's loaded into the data target. 
Britta has determined that a SQL database is the best solution for sharing the data in the hackathon.

![pic](https://github.com/ElenaMasarsky/Movies-ETL/blob/main/ratings_query.png)
![pic](https://github.com/ElenaMasarsky/Movies-ETL/blob/main/movies_query.png)
