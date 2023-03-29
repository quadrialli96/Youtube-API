# Youtube's-API
## I developed a fully automated data pipeline that continuously updates itself with the latest and most popular DataScience videos from YouTube..

### GOAL - The goal of this project is to identify the most valuable and informative YouTube channels for learning Data Science, in order to optimize and accelerate my learning journey in this field..

## Getting Started
#### - To obtain an API key, I set up a Google developer's account.
#### - "I consulted the documentation for the YouTube API to gain a better understanding of the data I could collect and the limitations of the API.
#### - After making a decision, I started collecting the necessary data and transformed it, which was eventually loaded into AWS RDS. 

## Prerequisites
#### - I utilized Jupyter Notebook as my Integrated Developer Environment.
#### - Libraries i used included:
         - Pandas for creating DataFrame.
         - Requests for making an http requests.
         - Psycopg2 to establish a connection between the PostgreSQL database I created on Amazon Web Services Relational Database and my program.
                          
                            
# Explanation of the Data Pipeline
#### - Extracting the most Popular data science Video From youtube's API 
 - Initially, my first API collectED features such as video_id, title, description, channel_title & upload_date.
 - The 2nd API call collected the statistics such as views, likes, favorites & comment.
 - Both of these DataFrames was then concatenated to make the DataFrame that i would then Deploy into AWS RDS PostgreSQL post transformation. 
 
#### - Importing Youtube's API Data into AWS RDB (PostgreSQL)
 - The notebook documented the steps I followed to establish a connection between my PostgreSQL database and AWS RDBS, using the psycopg2 adapter.
 - After providing my credentials, I established a connection to the database. 
 - In addition, I created, inserted, and updated a table with the collected data.. 
 
 
# Acknowledgments
 - Stackoverflow
 - ChatGpt
 - https://www.youtube.com/watch?v=fklHBWow8vE&list=WL&index=11&t=816s
 
 
