# 📊 CodeAlpha Data Analytics Internship

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Internship projects completed as part of the **CodeAlpha Data Analytics Internship Program**.  
> All tasks involve real-world data analysis, visualization, and machine learning techniques.

---

## 👤 Intern Details

| Field        | Details                        |
|--------------|--------------------------------|
| **Name**     | Sagar Patil                    |
| **Domain**   | Data Analytics                 |
| **Company**  | CodeAlpha                      |
| **Website**  | www.codealpha.tech             |

---

## 📁 Repository Structure

```
CodeAlpha/
│
├── Task1_WebScraping/
│   ├── CodeAlpha_WebScraping.ipynb
│   ├── scraped_books.csv
│   ├── ws_chart1_price_distribution.png
│   ├── ws_chart2_rating_distribution.png
│   ├── ws_chart3_price_vs_rating.png
│   ├── ws_chart4_expensive_books.png
│   ├── ws_chart5_cheap_books.png
│   └── ws_chart6_scatter.png
│
├── Task2_EDA/
│   ├── CodeAlpha_EDA.ipynb
│   ├── titanic.csv
│   └── titanic_eda.png
│
├── Task3_DataVisualization/
│   ├── CodeAlpha_DataVisualization.ipynb
│   ├── titanic.csv
│   ├── chart1_survival_count.png
│   ├── chart2_gender_survival.png
│   ├── chart3_class_survival.png
│   ├── chart4_age_analysis.png
│   ├── chart5_fare_boxplot.png
│   ├── chart6_pie_charts.png
│   ├── chart7_heatmap.png
│   └── chart8_full_dashboard.png
│
├── Task4_SentimentAnalysis/
│   ├── CodeAlpha_SentimentAnalysis.ipynb
│   ├── twitter_training.csv
│   ├── twitter_validation.csv
│   ├── chart1_sentiment_distribution.png
│   ├── chart2_sentiment_pie.png
│   ├── chart3_top_topics.png
│   ├── chart4_topic_sentiment.png
│   ├── chart5_wordclouds.png
│   ├── chart6_polarity_subjectivity.png
│   └── chart7_scatter.png
│
└── README.md
```

---

## ✅ Task 1 — Web Scraping

### 📌 Objective
Extract book data from [books.toscrape.com](http://books.toscrape.com) using Python.

### 🛠️ Tools Used
- `requests` — HTTP requests
- `BeautifulSoup` — HTML parsing
- `pandas` — Data handling
- `matplotlib` & `seaborn` — Visualization

### 📊 What Was Scraped
| Field        | Description                  |
|--------------|------------------------------|
| Title        | Book title                   |
| Price (£)    | Price in British pounds      |
| Rating       | Star rating (1–5)            |
| Availability | In stock / Out of stock      |
| Category     | Book genre/category          |

### 📈 Key Findings
- ✅ Scraped **1000 books** across **50 pages**
- 💰 Price range: **£10 – £60**
- ⭐ Most books rated **3–4 stars**
- 📚 **50 unique categories** available

### 🖼️ Sample Charts
| Chart | Description |
|-------|-------------|
| Price Distribution | Histogram of all book prices |
| Rating Distribution | Count of books per star rating |
| Price vs Rating | Box plot comparing price by rating |
| Top 10 Expensive | Most expensive books |
| Top 10 Cheapest | Most affordable books |

---

## ✅ Task 2 — Exploratory Data Analysis (EDA)

### 📌 Objective
Perform EDA on the **Titanic dataset** to uncover patterns and insights.

### 🛠️ Tools Used
- `pandas` — Data exploration
- `matplotlib` & `seaborn` — Visualization
- `numpy` — Numerical analysis

### 📊 Dataset Info
| Field       | Value       |
|-------------|-------------|
| Dataset     | Titanic     |
| Total Rows  | 891         |
| Total Cols  | 12          |
| Source      | GitHub (datasciencedojo) |

### 📈 Key Findings
- ✅ Overall survival rate: **38.4%**
- 👫 Female survival rate: **~74%** vs Male: **~18%**
- 🎫 1st class survival rate: **~63%** vs 3rd class: **~24%**
- 🎂 Average age of survivors: **28 years**
- ❓ Missing values found in: **Age**, **Cabin**, **Embarked**

---

## ✅ Task 3 — Data Visualization

### 📌 Objective
Transform Titanic data into compelling visual stories using multiple chart types.

### 🛠️ Tools Used
- `matplotlib` — Basic charts
- `seaborn` — Statistical visualizations
- `plotly` — Interactive charts

### 🖼️ Charts Created
| # | Chart Type | Insight |
|---|-----------|---------|
| 1 | Bar Chart | Survival count |
| 2 | Grouped Bar | Survival by gender |
| 3 | Grouped Bar | Survival by class |
| 4 | Histogram | Age distribution |
| 5 | Box Plot | Fare by class |
| 6 | Pie Chart | Survival rate & gender split |
| 7 | Heatmap | Feature correlations |
| 8 | Dashboard | All insights in one view |
| 9 | Plotly Scatter | Interactive age vs fare |

### 📈 Key Visual Insights
- 👩 Women had **4x higher** survival rate than men
- 💰 Higher fare = higher class = better survival
- 🎂 Children had higher survival priority
- 🚢 Southampton had the most passengers

---

## ✅ Task 4 — Sentiment Analysis

### 📌 Objective
Analyze Twitter data to classify sentiment as Positive, Negative, Neutral, or Irrelevant.

### 🛠️ Tools Used
- `TextBlob` — Sentiment scoring
- `nltk` — NLP preprocessing
- `wordcloud` — Word visualization
- `plotly` — Interactive charts

### 📊 Dataset Info
| Field            | Value                        |
|------------------|------------------------------|
| Dataset          | Twitter Entity Sentiment     |
| Training Tweets  | ~74,000                      |
| Validation Tweets| ~1,757                       |
| Sentiment Labels | Positive, Negative, Neutral, Irrelevant |

### 📈 Key Findings
- 🐦 Dataset covers **multiple brands/topics**
- 😊 Positive tweets dominate most brand topics
- 😠 Negative tweets highlight customer pain points
- 📊 TextBlob polarity average: slightly positive
- 🔍 High subjectivity found in most tweets

### 🖼️ Charts Created
| # | Chart | Description |
|---|-------|-------------|
| 1 | Bar Chart | Sentiment distribution (train & val) |
| 2 | Pie Chart | Sentiment share percentage |
| 3 | Bar Chart | Top 10 most discussed topics |
| 4 | Grouped Bar | Sentiment per topic |
| 5 | Word Cloud | Most common words per sentiment |
| 6 | Histogram | Polarity & subjectivity distribution |
| 7 | Scatter Plot | Polarity vs subjectivity by sentiment |

---

## 🛠️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/YourUsername/CodeAlpha.git
cd CodeAlpha
```

### 2. Install Required Libraries
```bash
pip install pandas matplotlib seaborn numpy plotly requests beautifulsoup4 nltk textblob wordcloud
```

### 3. Open Jupyter Notebook
```bash
jupyter notebook
```

### 4. Run Each Notebook
- Navigate to each task folder
- Open the `.ipynb` file
- Run all cells top to bottom using **Shift + Enter**

---

## 📦 Libraries Used

| Library       | Purpose                        |
|---------------|--------------------------------|
| pandas        | Data loading & manipulation    |
| numpy         | Numerical operations           |
| matplotlib    | Basic plotting                 |
| seaborn       | Statistical visualization      |
| plotly        | Interactive charts             |
| requests      | HTTP requests for scraping     |
| BeautifulSoup | HTML parsing                   |
| nltk          | NLP preprocessing              |
| TextBlob      | Sentiment analysis             |
| wordcloud     | Word cloud generation          |

---

## 📞 Contact

### 👤 Intern Contact
- 📱 **Phone:** +91 7498759265
- 📧 **Email:** sagarpatilsagar2002@gmail.com

### 🏢 CodeAlpha Contact
- 🌐 **Website:** [www.codealpha.tech](https://www.codealpha.tech)
- 📧 **Email:** services@codealpha.tech
- 💬 **WhatsApp:** +91 9336576683

---

## 🏆 Internship Completion

| Task | Status |
|------|--------|
| Task 1 — Web Scraping          | ✅ Completed |
| Task 2 — EDA                   | ✅ Completed |
| Task 3 — Data Visualization    | ✅ Completed |
| Task 4 — Sentiment Analysis    | ✅ Completed |

> ⭐ **All 4 tasks completed successfully!**

---

*This project was completed as part of the CodeAlpha Data Analytics Internship Program.*
