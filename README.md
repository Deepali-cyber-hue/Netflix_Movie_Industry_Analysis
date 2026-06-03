### Objective of Project###

The primary aim of this project is to analyse, by retrieving and assessing key data from seven years of data from the film sector. This will be done using the programming language Python with a focus on the data analysis tool Pandas.

This project aims to identify trends in movie publication and metrics of film popularity. The aim is to address several questions, including:

* How many films were published per annum?

* Which genres of films are most widely accepted?

* What are the most commonly used spoken language for the release of films?

* Do the films that are most widely accepted correlate with films that are most popular?

* How is the film industry performing today?

### Data Collection Tools###

1.Programming language: Python
2.Data analysis library: Pandas
3.Mathematical library: NumPy
4.Graphical display library: Matplotlib

Information About the Data Set
There are a total of 9,837 records in the database, and the table below displays the attributes of the database.

#Attributes#:
Release_Date 
Title 
Overview 
Popularity 
Vote_Count 
Vote_Average 
Original_Language 
Genre 
Poster_Url 
Data Clean-up Process
The following data cleaning procedures were performed on the dataset:

Removal of Missing Data
Removal of Invalid Data
Correction of Data Types
Conversion of Release Date to Datetime
Extraction of Year from Release Date

There are 4 types of analyses that I performed on the data:

Language Analysis:

- I analyzed the languages that were used in the films.
- Key finding: There were the greatest number of films produced in the English Language, followed by Japanese and Spanish.

Genre Analysis:

- I used explode() to separate multi-genre entries and calculated the actual number of films for each genre.
- Key finding: The greatest number of films produced was in the Drama genre, followed by the Comedy and Action genres.

Release Year Analysis:

- I analyzed the movie production trends from each year to determine how much production has changed from one year to another.
- Key finding: Movie production has increased significantly over the past several decades and has peaked in the last few years at approximately 2021.

Popularity vs. Rating Analysis:

- I analyzed the correlation between how popular a film was compared to what people rated that same film.
- Key finding: There was a very weak correlation between these two variables (r=0.054), indicating that high popularity does not ensure high ratings.

The project includes visualizations of:

- Top Genres Bar Chart
- Movies Released Per Year Trend
- Popularity vs Rating Scatter Plot

Based on these analyses, the following conclusions were made:

1. There is a very strong dominance of English films.
2. The majority of films produced are either Drama or Comedy.
3. There is very little correlation between popularity and film rating.

Overall, this project demonstrates the capability of working with Pandas to clean, manipulate, aggregate, explore, and visualize data.
