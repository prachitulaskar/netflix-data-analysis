# 🎬 Netflix Data Analysis

## 📌 Project Overview

This project analyzes the Netflix Movies and TV Shows dataset using **Python**, **Pandas**, and **Matplotlib**. The objective is to clean the dataset, perform exploratory data analysis (EDA), visualize key trends, and extract meaningful insights about Netflix's content library.

---

## 📂 Dataset

* **Dataset:** Netflix Movies and TV Shows
* **Source:** Kaggle
* **Records:** 8,807 titles
* **Features:** 12 original columns

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📁 Project Structure

```text
netflix-data-analysis/
│
├── data/
│   ├── netflix_titles.csv
│   └── cleaned_netflix_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
└── README.md
```

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked the dataset structure and summary statistics.
* Identified missing values.
* Filled missing values in categorical columns.
* Converted the `date_added` column to datetime format.
* Removed rows with invalid or missing dates.
* Checked for duplicate records.
* Created new features:

  * `year_added`
  * `month_added`
* Saved the cleaned dataset for future use.

---

## 📊 Exploratory Data Analysis (EDA)

The project answers the following questions:

1. Movies vs TV Shows on Netflix
2. Content Added to Netflix Each Year
3. Top 10 Countries with the Most Netflix Content
4. Top 10 Directors on Netflix
5. Distribution of Content Ratings
6. Top 10 Genres on Netflix
7. Movies Released Each Year

---

## 📈 Key Insights

* Movies make up the majority of Netflix's content library.
* Netflix experienced rapid growth in content additions over the years.
* The United States contributes the highest number of titles.
* A small number of directors have multiple titles available on Netflix.
* TV-MA and TV-14 are among the most common content ratings.
* International Movies, Dramas, and Comedies are among the most popular genres.
* Most movies available on Netflix were released in recent years.

---

## ▶️ How to Run the Project

1. Clone the repository.

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib jupyter
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all cells to reproduce the analysis.

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Data Preprocessing
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Extracting insights from real-world datasets
* Working with Jupyter Notebook and GitHub
