# 🎬 Netflix Movies and TV Shows Data Analysis Using SQL

## 📌 Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows dataset using **SQL (MySQL)**.  
The goal is to extract valuable insights and answer business questions that highlight Netflix’s content distribution, trends, and market strategies.

---

## 🎯 Objectives
- Analyze the distribution of content types (Movies vs. TV Shows).  
- Identify the most common ratings for Movies and TV Shows.  
- Explore release years, countries, and content durations.  
- Categorize content based on genres, keywords, and other attributes.  

---

## 📂 Dataset
- **Source:** [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
- **Rows:** 8,807  
- **Columns:** 12 (title, director, cast, country, release_year, rating, duration, listed_in, description, etc.)  
- **Description:** Contains details of movies and TV shows available on Netflix (genre, release year, cast, director, duration, description, etc.)  

---

## ❓ Business Questions & Key Insights
| #  | Question | Key Insight |
|----|-----------|-------------|
| 1  | Count the number of Movies vs TV Shows | Movies dominate Netflix’s library (6,131 vs 2,676). |
| 2  | Most common rating for Movies & TV Shows | **TV-MA** is the most frequent rating overall. |
| 3  | Movies released in 2020 | Provides release trend for that year. |
| 4  | Top 5 countries with most content | US (3,211), India (1,008), UK (628) lead the chart. |
| 5  | Longest Movie | Identified Netflix’s maximum-length production. |
| 6  | Content added in last 5 years | Shows recent content growth. |
| 7  | Movies/TV Shows by director 'Jay Karas' | Profiles specific creator’s work. |
| 8  | TV Shows with more than 5 seasons | Identifies long-running series. |
| 9  | Count content items in each genre | Top genres: International Movies (2,752), Dramas (2,427). |
| 10 | Yearly % share of Indian content | 33.37% surge in 2018 (349 titles). |
| 11 | All Movies that are Documentaries | Segments non-fiction category. |
| 12 | Content without a director | Highlights missing metadata. |
| 13 | Movies with Salman Khan in last 10 years | Tracks one actor’s Netflix presence. |
| 14 | Top 10 actors in Indian Movies | Anupam Kher (40) & Shah Rukh Khan (34) dominate. |
| 15 | Content with 'kill' or 'violence' in description | Identifies potentially violent content. |

---

## 🛠 Tools & Technologies
- **Database:** MySQL  
- **Dataset:** Kaggle Netflix dataset  
- **SQL Concepts Used:**
  - Aggregation: `COUNT`, `GROUP BY`, `SUM`
  - Conditional logic: `CASE WHEN`
  - String operations: `LIKE`, `SUBSTRING_INDEX`
  - Date operations: `YEAR()`, `CURDATE()`
  - Filtering: `WHERE`, `IS NULL`
  - Sorting & Limiting: `ORDER BY`, `LIMIT`
  - Subqueries & Joins
  - Common Table Expressions (CTEs) & Window Functions

---

## 📊 Key Findings
- **Content Mix:** Movies dominate (6,131) vs TV Shows (2,676).  
- **Ratings:** Most frequent rating is **TV-MA**.  
- **Geographic Distribution:** US (3,211 titles) > India (1,008) > UK (628).  
- **Genres:** International Movies (2,752) and Dramas (2,427) lead.  
- **Indian Trends:** In 2018, India released 349 titles (33.37% of its total).  
- **Top Indian Actors:** Anupam Kher (40 movies), Shah Rukh Khan (34).  
- **Content Sentiment:** Descriptions mostly classified as *Positive*.  

---

## 🚀 How to Run the Project
1. Download dataset from Kaggle and save as `netflix_titles.csv`.  
2. Import the CSV into MySQL using Workbench or CLI.  
3. Execute queries from the provided SQL file in order.
4.Review results and insights for each question.
