# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends, patterns, and insights about genres, popularity, ratings, and release history.

---

## 📌 Project Overview

This project performs a comprehensive EDA on a dataset of **9,826 Netflix movies** sourced from TMDB (The Movie Database). The analysis explores:

- Genre distribution and frequency
- Popularity trends across genres
- Vote averages and audience ratings
- Movie release trends over the years
- Language diversity across the catalog

---

## 📂 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full analysis
├── NetflixData.csv               # Dataset (add manually or link source)
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

The dataset contains **9,826 rows** and **9 columns**:

| Column | Description |
|---|---|
| `Release_Date` | Movie release date |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score (TMDB metric) |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average user rating (0–10) |
| `Original_Language` | Language of the original movie |
| `Genre` | One or more genres |
| `Poster_Url` | URL to the movie poster image |

> **Note:** Place `NetflixData.csv` in the same directory as the notebook before running.

---

## 🔍 Key Insights

- **Drama** is the most frequently occurring genre on Netflix.
- **Adventure** movies have the highest average popularity score.
- **Action** and **Science Fiction** also draw strong audience interest.
- Movie releases grew significantly **after the year 2000**, reflecting the rise of digital streaming.
- Popularity is **highly skewed** — most movies are average, while only a few become blockbuster hits.

---

## 📈 Visualizations

The notebook includes interactive charts built with **Plotly Express**:

- Bar chart of genre frequency
- Average popularity by genre
- Distribution of vote averages
- Movie release count over the years
- Popularity distribution histogram

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — data loading and manipulation
- **Plotly Express** — interactive visualizations
- **Google Colab** — development environment

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

### 3. Add the dataset

Place `NetflixData.csv` in the root project folder.

### 4. Run the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

Or open it directly in [Google Colab](https://colab.research.google.com/).

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Made with ❤️ for data exploration and storytelling through data.
