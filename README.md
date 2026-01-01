# 🎬 Movie Ratings & Popularity Analysis (EDA)

An exploratory data analysis (EDA) project focused on understanding **movie ratings, audience engagement, and popularity trends** using a Kaggle movie dataset.

This project emphasizes **data understanding, cleaning decisions, and insight-driven analysis** rather than just visualization.

---

## 📌 Project Overview

Movies receive ratings from audiences worldwide, but **ratings alone don’t tell the full story**.  
This project explores how **ratings and vote counts interact**, identifies popular vs well-rated movies, and handles **real-world data challenges** such as duplicate identifiers and alternate titles.

---

## 📂 Dataset Description

The dataset contains movie-level information with the following key columns:

| Column Name | Description |
|------------|------------|
| `titleId` | Unique identifier for each movie |
| `title` | Movie title (can include alternate or localized titles) |
| `averageRating` | Average user rating |
| `numVotes` | Total number of votes received |

> ⚠️ Note: Some movies appear multiple times due to **localized or alternate titles**, not data errors.

---

## 🔍 Key Questions Explored

1. How many movies are present in the dataset?
2. What is the overall average movie rating?
3. Which movies are the highest and lowest rated?
4. Which movies received the most and fewest votes?
5. Is there a relationship between ratings and popularity?
6. Do highly rated movies always receive more votes?
7. How should duplicate `titleId`s with different titles be handled?
8. What defines a movie as both **popular and well-rated**?

---

## 🧠 Key Insights

- Repeated `titleId`s with different titles represent **localized or alternate movie titles**, not true duplicates.
- True duplicates were removed safely without data loss.
- Popular movies (high votes) do not always have the highest ratings.
- Ratings and vote counts show **weak-to-moderate correlation**, highlighting different audience behaviors.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Kaggle Notebooks**

---
