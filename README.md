# Movies-ETL

## *Project Overview*
*Britta needs help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We have to refactor the code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.*

## *Resources*
*Anaconda, Jupyter Notebook, Python, PostgreSQL / PgAdmin*

## *Analysis*

<img width="960" alt="movies_query" src="https://user-images.githubusercontent.com/89530570/142764365-eea55538-7c37-41d5-b4ed-79bb468bf39d.png">

<img width="960" alt="ratings_query" src="https://user-images.githubusercontent.com/89530570/142764382-f3dd39ac-0d25-41ca-80b6-721d7355a390.png">


## *Summary*
*ETL function is written to read in the three data files. Have used Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so we can merge it with the Kaggle metadata. TV Shows are filtered out. The box office, budget, release date, running time colums are cleaned. Python, Pandas, the ETL process, code refactoring, and PostgreSQL are used to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.*
