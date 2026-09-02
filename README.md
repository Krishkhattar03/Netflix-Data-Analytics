
# 🎬 Netflix Data Analytics

An end-to-end data analytics project analyzing Netflix's content library using Python, MySQL, SQL, Power BI, and DAX.

The project follows a complete analytics workflow — from data ingestion and database creation to data cleaning, SQL analysis, data modeling, and interactive dashboard development.

---

## 📌 Project Overview

This project analyzes Netflix titles to understand content distribution, growth trends, genres, ratings, countries, directors, cast members, movie durations, and TV show seasons.

The project was built as a complete data analytics pipeline rather than only a visualization project.



# 🔄 Project Workflow

## 1. Data Loading using Python

Python was used to establish the database connection and load the Netflix dataset into MySQL.

### Key activities

- Database connection
- Data ingestion
- Loading raw Netflix data into MySQL
- Preparing the dataset for transformation and analysis

---

## 2. Data Cleaning & Transformation

The raw Netflix data was cleaned and transformed using SQL and Power Query.

### Key activities

- Handling missing values
- Cleaning inconsistent data
- Transforming columns
- Processing multi-valued fields
- Creating normalized tables
- Preparing data for analytical queries

---

## 3. Data Modeling

A dimensional data model was created to support efficient analysis in Power BI.

The model includes the main Netflix titles table along with supporting dimension and bridge tables for:

- Countries
- Genres
- Directors
- Cast Members

This structure allows the dashboard to analyze Netflix content across multiple dimensions.

---

## 4. SQL Analysis

SQL was used to answer business and analytical questions about Netflix's content library.



## 🔍 SQL Analysis Questions

The following business questions were answered using SQL:

1. Which directors have created both Horror and Comedy movies?
   - Display the director name along with the number of Comedy and Horror movies directed by each director.

2. What is the average movie duration for each director listed in the previous analysis?

3. For each year, based on the date content was added to Netflix, which director released the maximum number of movies?

4. Which country has the highest number of Comedy movies?

5. For each director, what is the number of Movies and TV Shows they have created?
   - Display Movies and TV Shows in separate columns.
   - Include only directors who have created both Movies and TV Shows.

---

# 📊 Power BI Dashboard

The final Power BI solution contains five interactive pages.

---

## 1️⃣ Executive Overview

Provides a high-level overview of Netflix's content library.

### Includes

- Total Titles
- Total Movies
- Total TV Shows
- Total Countries
- Total Genres
- Total Directors
- Content Growth Over the Years
- Movies vs TV Shows
- Top Genres
- Top Countries
- Rating Distribution
- Key Insights

![Executive Overview](https://github.com/Krishkhattar03/Netflix-Data-Analytics/blob/main/1.jpeg)

---

## 2️⃣ Content Analysis

Focuses on the characteristics of Netflix content.

### Includes

- Movies and TV Shows by Release Year
- Content Type Distribution by Rating
- Movies by Duration
- TV Shows by Number of Seasons
- Average Movie Duration
- Average TV Show Seasons

![Content Analysis](https://github.com/Krishkhattar03/Netflix-Data-Analytics/blob/main/2.jpeg)

---

## 3️⃣ Geographic Analysis

Explores Netflix's content distribution across countries.

### Includes

- Titles by Country
- Top Countries by Number of Titles
- Content Added by Country Over Time
- Country-wise Content Breakdown
- Geographic distribution of Netflix titles

![Geographic Analysis](https://github.com/Krishkhattar03/Netflix-Data-Analytics/blob/main/3.jpeg)

---

## 4️⃣ People & Creators

Analyzes the directors and cast members associated with Netflix content.

### Includes

- Top 10 Directors by Number of Titles
- Top 10 Cast Members by Number of Titles
- Directors by Content Type
- Director Details
- Director and cast-level analysis

![People & Creators](https://github.com/Krishkhattar03/Netflix-Data-Analytics/blob/main/4.jpeg)

---

## 5️⃣ Content Explorer

Provides an interactive title-level exploration interface.

### Filters

- Title
- Type
- Country
- Genre
- Rating
- Release Year
- Director

### Details

The table allows users to explore individual Netflix titles along with:

- Title
- Type
- Release Year
- Rating
- Duration
- Country
- Director

![Content Explorer](https://github.com/Krishkhattar03/Netflix-Data-Analytics/blob/main/5.jpeg)

---

# 📈 Key Insights

The analysis highlights several patterns within the Netflix catalog:

- Movies represent the majority of Netflix titles.
- The United States is the largest contributor of Netflix content.
- Netflix's content library expanded significantly during the 2010s.
- International Movies and Dramas are among the largest genre categories.
- Netflix TV Shows are concentrated heavily around a small number of seasons.
- Content distribution varies significantly across countries and ratings.


