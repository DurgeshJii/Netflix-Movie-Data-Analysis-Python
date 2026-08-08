# 🎬 Netflix Movie Data Analysis Using Python

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a movie dataset containing 9,827 records.

The objective is to analyze movie genres, ratings, popularity scores and release-year trends using Python and data visualization techniques.

The project focuses on converting raw movie metadata into meaningful insights that can help understand content distribution and movie performance.

---

## 🎯 Objectives

The analysis answers the following questions:

1. What is the most frequent movie genre?
2. Which movies have the highest Vote Average?
3. Which movie has the highest popularity and what is its genre?
4. Which movie has the lowest popularity and what is its genre?
5. Which year has the highest number of movies?

---

## 📂 Dataset

The dataset contains 9,827 movie records and 9 columns:

- Release_Date
- Title
- Overview
- Popularity
- Vote_Count
- Vote_Average
- Original_Language
- Genre
- Poster_Url

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔎 Data Analysis Process

### 1. Data Loading

The dataset was loaded using Pandas.

### 2. Data Inspection

Used:

- `head()`
- `info()`
- `describe()`

to understand the dataset structure and numerical distributions.

### 3. Genre Analysis

The Genre column contains multiple genres in a single field.

The genres were:

- split using `str.split()`
- transformed into individual rows using `explode()`
- cleaned using `str.strip()`
- counted using `value_counts()`

### 4. Rating Analysis

Movies were sorted according to `Vote_Average` to identify the highest-rated movies.

### 5. Popularity Analysis

The dataset was sorted by `Popularity` to identify both the highest- and lowest-popularity movies.

### 6. Time-Series Analysis

`Release_Date` was converted to datetime format and the release year was extracted.

Movie counts were then calculated for each year.

### 7. Visualization

Bar charts were created using Matplotlib and Seaborn.

---

## 📊 Key Findings

### 🎭 Most Frequent Genre

Drama is the most frequent genre with:

**3,744 movies**

Other leading genres:

| Genre | Count |
|---|---:|
| Drama | 3,744 |
| Comedy | 3,031 |
| Action | 2,686 |
| Thriller | 2,488 |
| Adventure | 1,853 |
| Romance | 1,476 |
| Horror | 1,470 |
| Animation | 1,439 |
| Family | 1,414 |
| Fantasy | 1,308 |

---

### ⭐ Highest Vote Average

The movie with the highest Vote Average is:

**Kung Fu Master Huo Yuanjia**

- Vote Average: **10.0**
- Vote Count: **1**
- Genre: Action, Drama

Because it has only one vote, the 10.0 rating should not be interpreted as evidence that it is the most reliably highly-rated movie.

---

### 🔥 Most Popular Movie

**Spider-Man: No Way Home**

- Popularity: **5,083.954**
- Genre: Action, Adventure, Science Fiction

Top 5 by popularity:

1. Spider-Man: No Way Home
2. The Batman
3. No Exit
4. Encanto
5. The King's Man

---

### 📉 Lowest Popularity

The movie with the lowest popularity is:

**The United States vs. Billie Holiday**

- Popularity: **13.354**
- Genre: Music, Drama, History

---

### 📅 Year with Most Movies

**2021 — 714 movies**

Top 5 years:

| Year | Movie Count |
|---|---:|
| 2021 | 714 |
| 2018 | 530 |
| 2017 | 510 |
| 2019 | 500 |
| 2016 | 470 |

---

## 📈 Visualizations

The project includes:

### 1. Top 10 Movie Genres

Shows the most frequently occurring genres.

### 2. Top 10 Movies by Vote Average

Compares the highest movie ratings.

### 3. Top 5 Most Popular Movies

Compares movies using popularity scores.

### 4. Top 5 Years with Most Movies

Shows years with the highest movie counts.

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

- Data loading
- Data inspection
- Data cleaning
- String preprocessing
- Handling multi-value categorical columns
- Aggregation
- Sorting and filtering
- Datetime conversion
- Ranking analysis
- Exploratory Data Analysis
- Data visualization
- Extracting business-oriented insights

---

## ⚠️ Important Analytical Note

Popularity, Vote Average and Vote Count represent different dimensions.

A movie with a very high Vote Average but only a few votes should not automatically be considered the best-rated movie.

This project therefore demonstrates the importance of considering multiple metrics before drawing conclusions.

---

## 🚀 Future Improvements

Possible extensions include:

- Genre-wise average ratings
- Popularity vs. Vote Count correlation
- Language-wise movie distribution
- Release trends over time
- Top directors/actors analysis if those fields are available
- Interactive dashboard using Power BI
- Interactive Python dashboard using Streamlit
- Recommendation system based on movie attributes

---

## 👨‍💻 Author

**Durgesh Yadav**

Aspiring Data Analyst / Data Scientist

Skills:
Python | SQL | Power BI | Excel | Statistics | Machine Learning | Data Visualization
