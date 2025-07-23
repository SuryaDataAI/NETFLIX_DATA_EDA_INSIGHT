# 🎬 Netflix EDA Insights – Exploratory Data Analysis on Netflix Titles

Welcome to this in-depth EDA project where we analyze **Netflix's catalog of Movies and TV Shows** using Python 🐍. This project uncovers patterns, content trends, and insights using real-world data.

---

## 🔍 About the Dataset

- 📦 **Source**: [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- 🧾 **Rows**: 8807  
- 📊 **Columns**: 12 (type, title, director, cast, country, date added, release year, rating, duration, genres, description)

---

## 📈 Project Objectives

✅ Perform 30+ industry-relevant EDA techniques  
✅ Clean and preprocess data (handling missing values, date conversions)  
✅ Visualize data with Matplotlib and Seaborn  
✅ Extract meaningful insights about Netflix content  
✅ Build a shareable GitHub portfolio project  

---

## 🛠️ Tools and Libraries Used

- Python 3.x 🐍  
- Pandas 🧮  
- NumPy 🔢  
- Matplotlib 📊  
- Seaborn 🌈  
- WordCloud ☁️  
- Jupyter Notebook 📓

---

## 🧪 EDA Highlights

Some of the questions answered:
- 🎬 What is the distribution of Movies vs TV Shows?
- 🌍 Which countries produce the most content?
- 🗓️ What years saw the most releases or additions?
- ⏱️ What is the typical duration of movies and TV shows?
- 👨‍🎓 What are the top genres and directors?
- 📈 What are the most common ratings?
- 🧼 How many rows have missing director or cast fields?

> 🔍 A total of **30+ techniques** were applied using `value_counts()`, `groupby()`, visualizations, and custom feature extraction.

---

## 📸 Sample Visualizations

| Type Trends | Genre WordCloud |
|-------------|-----------------|
| ![Type Chart](assets/type_trend.png) | ![Word Cloud](assets/genre_wordcloud.png) |

---

## 📁 Folder Structure

```bash
netflix-eda-insights/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_eda.ipynb
├── assets/
│   ├── genre_wordcloud.png
│   └── type_trend.png
├── README.md
└── requirements.txt





 What I Learned
Mastered real-world dataset cleaning and exploration

Practiced critical thinking through data questioning

Improved data visualization and storytelling

Learned feature engineering and derived insights.
.
.
.
.


How to Run
Clone the repository
git clone https://github.com/your-username/netflix-eda-insights.git
Install dependencies
pip install -r requirements.txt
Run the Jupyter Notebook
jupyter notebook notebooks/netflix_eda.ipynb


🌟 Future Improvements
Add interactive dashboards (e.g., Plotly/Dash)
Perform NLP on description field
Predict rating or genre using ML.

Venkata Surya.


 If you found this project helpful...
Give it a ⭐️ on GitHub and feel free to fork, clone, or contribute!


---

### ✅ `requirements.txt` Example

```txt
pandas
numpy
matplotlib
seaborn
wordcloud
jupyter
