# Movies-ETL

![image202](https://user-images.githubusercontent.com/58860105/136827367-59396828-6807-4837-b8eb-413a9e1d8fa8.PNG)

Perform the Extract, Transform, and Load (ETL) process to create a data pipeline on movie datasets using Python, Pandas, Jupyter Notebook and PostgreSQL.

In this project, I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.  Refactored the code from the module challenge and created one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.


## Deliverable 1

Using knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

## Wiki_movies_df DataFrame

![movies df](https://user-images.githubusercontent.com/58860105/136827910-390a2a98-4eb4-4ac6-90e3-15ed95d817b7.PNG)


## kaggle_metadata DataFrame

![kaggledf](https://user-images.githubusercontent.com/58860105/136828042-b5e60f03-d663-4a21-8a82-5594a9938088.PNG)


## Deliverable 2

Using knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

## wiki_movies_df
![delv2 1](https://user-images.githubusercontent.com/58860105/136828479-cd06b792-ab12-4bf5-82cb-0a256fb2473e.PNG)



## wiki_movies_df
![delv2 2](https://user-images.githubusercontent.com/58860105/136828493-c3ec1226-a8e7-4f05-bbd6-b77e518fa19a.PNG)


## Deliverable 3
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

## movies_with_ratings_df
![dev3 1](https://user-images.githubusercontent.com/58860105/136828812-3da66824-4285-423d-94c3-1da4bfa8b942.PNG)



## movies_df
![dev3 2](https://user-images.githubusercontent.com/58860105/136828875-0f08635f-03aa-4b17-93c3-e668943d13fc.PNG)

## Deliverable 4
Use knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
![movies_query2](https://user-images.githubusercontent.com/58860105/136829019-77dbded0-3fd1-4ed2-9689-ead49aea2ca4.PNG)

![movies_query1](https://user-images.githubusercontent.com/58860105/136829026-4f83977c-67d0-4949-8a7b-556e80bd3d3a.PNG)


![ratings_query1](https://user-images.githubusercontent.com/58860105/136829040-300c3692-bba3-4c13-83ce-a3b38339f1d4.PNG)

![ratings_query2](https://user-images.githubusercontent.com/58860105/136829055-8e388639-d67c-4120-8a87-24dad6071887.PNG)



# Summary
The (Extract, Transform, Load) function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings CSV files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
