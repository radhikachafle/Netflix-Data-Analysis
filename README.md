# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of Netflix movies and TV shows dataset to uncover trends, patterns, and insights about content popularity, genres, and audience preferences.

---

## 📋 Project Overview

This project performs a comprehensive EDA on a Netflix dataset using Python. It explores various aspects of the data — from genre distributions and popularity scores to release trends over time — and presents findings through interactive visualizations built with Plotly.

---

## 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full analysis
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

**File:** `NetflixData.csv`

The dataset contains information about Netflix movies with the following columns:

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average user rating |
| `Original_Language` | Language the movie was originally produced in |
| `Genre` | Genre(s) of the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Performed

- **Data Loading & Preview** — Loading the CSV and inspecting the first few rows
- **Data Cleaning** — Handling missing values and fixing data types
- **Genre Analysis** — Most common genres and average popularity by genre
- **Language Distribution** — Breakdown of movies by original language
- **Release Trend** — Number of movie releases over the years
- **Popularity Distribution** — Distribution and skewness of popularity scores
- **Vote Analysis** — Vote count and average rating patterns

---

## 📈 Key Insights

- **Drama** is the most frequently occurring genre on Netflix.
- **Adventure** movies have the highest average popularity among all genres.
- **Action** and **Science Fiction** also attract high audience engagement.
- Movie releases increased significantly **after the year 2000**, reflecting the rapid growth of the streaming industry.
- The popularity distribution is **highly skewed** — most movies are average, with only a few becoming major hits.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — Data manipulation and analysis
- **Plotly Express** — Interactive visualizations
- **Jupyter Notebook** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** If you're running on Google Colab, upload `NetflixData.csv` to `/content/` and run all cells directly.

---

## ☁️ Run on Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Upload both `Netflix_Data_Analysis.ipynb` and `NetflixData.csv` to your Colab session and run all cells.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, additional analyses, or bug fixes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
