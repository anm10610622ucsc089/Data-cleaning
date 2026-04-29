# 📊 Data Cleaning & Visualization Project (Netflix Dataset)

## 📌 Overview

This project focuses on cleaning, processing, and analyzing a real-world dataset using Python. The dataset used contains information about movies and TV shows available on Netflix.

The goal is to transform raw data into meaningful insights through data cleaning and visualization techniques.

---

## 📂 Dataset

* **Dataset Name:** Netflix Titles Dataset
* **Format:** CSV
* **Source:** Kaggle

The dataset includes details such as:

* Title
* Director
* Cast
* Country
* Release Year
* Date Added
* Rating
* Duration
* Genre (Listed In)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas (Data Cleaning & Manipulation)
* NumPy (Numerical Operations)
* Matplotlib (Visualization)
* Seaborn (Statistical Visualization)

---

## 🧹 Data Cleaning Steps

The following preprocessing steps were performed:

* Removed duplicate records
* Handled missing values:

  * Replaced missing `director` with **"Unknown"**
  * Replaced missing `cast` with **"Not Available"**
  * Replaced missing `country` with **"Unknown"**
  * Filled missing `rating` with the most frequent value
* Converted `date_added` to datetime format
* Extracted `year_added` from the date column

---

## 📊 Exploratory Data Analysis (EDA)

Key analyses performed:

* Distribution of Movies vs TV Shows
* Content added over the years
* Top countries producing Netflix content
* Most common genres
* Ratings distribution
* Trends in content growth

---

## 📈 Visualizations

The project includes various visualizations such as:

* Bar charts
* Count plots
* Histograms
* Heatmaps (if applicable)

These visualizations help uncover patterns and trends in the dataset.

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Data-cleaning.git
```

2. Navigate to the project folder:

```bash
cd Data-cleaning
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run the notebook:

```bash
jupyter notebook Analysis.ipynb
```

---

## 📌 Key Insights

* Netflix has significantly increased content over recent years
* Movies dominate the platform compared to TV shows
* Certain countries contribute more content than others
* Popular genres can be identified through frequency analysis

---

## 📎 Project Structure

```
Data-cleaning/
│
├── Analysis.ipynb        # Main notebook
├── netflix_titles.csv   # Dataset
└── README.md            # Project documentation
```

---

## 🙌 Conclusion

This project demonstrates how raw data can be transformed into meaningful insights through effective data cleaning and visualization techniques.

---

## 📬 Contact

For questions or collaboration, feel free to reach out!

---
