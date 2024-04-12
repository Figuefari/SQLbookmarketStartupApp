## Proyect description 
Analysis of the book market to generate a new value proposition for a startup aiming to develop a new application. We studied the database using SQL.

## Tasks
1. Describe the study objectives.
2. Study the tables.
3. Perform SQL queries for the following tasks:
   - Find the number of books published after January 1, 2000.
   - Identify the publisher that has published the highest number of books with more than 50 pages.
   - Identify the author with the highest average rating of books.
   - Find the average number of text reviews among users who rated more than 50 books.
4. Generate query results.
5. Describe conclusions for each task.

## Data Description

1. books:

   - book_id — book identification
   - author_id — author identification
   - title — title
   - num_pages — number of pages
   - publication_date — publication date
   - publisher_id — publisher identification

2. authors:

   - author_id — author identification
   - author — author

3. publishers:

   - publisher_id — publisher identification
   - publisher — publisher

4. ratings:

   - rating_id — rating identification
   - book_id — book identification
   - username — username of the user who reviewed the book
   - rating — rating

5. reviews:

   - review_id — review identification
   - book_id — book identification
   - username — username of the user who reviewed the book
   - text — review text

## Table of Contents

1. Initialization
    - Libraries
    - Database Access
     
2. Data Study
    - Specific Objectives
    - Tables
    - Data Description

3. SQL Queries

4. Conclusions and Recommendations

## Used libraries

- pandas
- sqlalchemy

