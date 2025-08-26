# 🎬 Netflix Movies EDA Project

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a Netflix-like movie dataset to explore trends, popularity, genres, ratings, and votes.  
The goal is to uncover meaningful insights such as the most frequent genres, highest/lowest popularity movies, and yearly film production trends.

---

## 📂 Dataset
- **Columns include**:
  - `Release_Date` : Date when the movie was released  
  - `Title` : Name of the movie  
  - `Overview` : Short description of the movie  
  - `Popularity` : Popularity score (from TMDB/Netflix dataset)  
  - `Vote_Count` : Number of votes received  
  - `Vote_Average` : Average rating  
  - `Original_Language` : Language of the movie  
  - `Genre` : Movie genre(s)  
  - `Poster_Url` : Link to the movie poster  

---

## 🔍 Key Analysis
The analysis covers:
- Most frequent genres in the dataset  
- Highest voted genres  
- Movies with the highest and lowest popularity  
- Year with the highest number of released movies  

---

## 📊 Visualizations
Some of the plots included in this project:
- Distribution of movie genres  
- Popularity trends across movies  
- Votes vs Average rating scatter plots  
- Yearly movie release trends  
- Word clouds for overviews & genres  

---

## 📈 Results & Insights

**Q1: What is the most frequent genre in the dataset?**  
➡️ *Drama* is the most frequent genre, appearing more than 14% of the times among 19 other genres.  

**Q2: What genres have the highest votes?**  
➡️ Drama again dominates, with more than **25.5% (6520 rows)** of the dataset having popular votes.  

**Q3: Which movie got the highest popularity? What's its genre?**  
➡️ *Spider-Man: No Way Home* is the most popular movie with genres **Action, Adventure, Science Fiction**.  

**Q4: Which movie got the lowest popularity? What's its genre?**  
➡️ *The United States, Thread* has the lowest popularity. Its genres include **Music, Drama, War, Sci-Fi, and History**.  

**Q5: Which year has the most films released?**  
➡️ Year **2020** recorded the highest number of films released in the dataset.  

---

## 🛠️ Technologies Used
- **Python**  
- **Libraries**:
  - `pandas` → Data manipulation & cleaning  
  - `numpy` → Numerical computations  
  - `matplotlib` & `seaborn` → Visualization  
  - `plotly` → Interactive visualizations  
  - `wordcloud` → Word cloud generation  
