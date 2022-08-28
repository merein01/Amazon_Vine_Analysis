# Amazon_Vine_Analysis
# Overview
For this project, we analyzed Amazon Vine program to determine if there is a bias towards favorable reviews posted by vine members against non-vine members. We used Pyspark in performing the ETL process. We first extracted the data, then transformed the data, connected to AWS RDS, loaded the transformed data using Postgres SQL into pgAdmin, and calculated different metrics. We were given a choose of datasets from Amazon reviews and chose to focus on US reveiws for video games.
# Results

Total Number of Reviews

Vine Reviews

<img width="263" alt="Vine Reviews" src="https://user-images.githubusercontent.com/105119376/187051483-6e22f364-38e7-4bce-b1cc-9c2a5b3e598b.png">

Non-Vine Reviews

<img width="264" alt="Total Non-Vine reviews" src="https://user-images.githubusercontent.com/105119376/187051492-50046a0a-0d76-47d9-85ea-2395bcc5d73e.png">

Total Number of 5-star Reviews

Vine Reviews 

<img width="442" alt="Total Vine 5-star" src="https://user-images.githubusercontent.com/105119376/187051496-685466be-c5d6-48b6-a870-7f00629ab323.png">

Non-Vine Reviews

<img width="479" alt="Total Non-Vine 5-star reviews" src="https://user-images.githubusercontent.com/105119376/187051502-c089da93-652a-4189-befa-889ea7355527.png">

5-Star Percentage

Vine Reviews

<img width="475" alt="Vine Percentage" src="https://user-images.githubusercontent.com/105119376/187051506-eb61488d-f4d0-457d-b9f7-1e38e7e48741.png">

Non-Vine Reviews

<img width="485" alt="Non Vine Percentage" src="https://user-images.githubusercontent.com/105119376/187051508-e0256a05-f890-4f57-8540-d99bd3a568f5.png">

# Summary 
According to the caluclations performed, 51% of the reviews were Vine reviews, however 39% of the reviews were non-Vine. This metric prooves a positivity bias for reviews in the Amazon Vine program. An additional analysis we could perform is analyzing the ratings based on verified purchase vs non-verified purchase. This could show a better distribution of the data.
