# Twitter Behavior Analysis: Elon Musk, Kanye West, and Russian Bot Accounts

This project analyzes Twitter activity patterns for Elon Musk, Kanye West, and a dataset of Russian Internet Research Agency (IRA) bots.  
It explores posting frequency, sentiment, and behavioral differences before and after key events like Elon Musk’s Twitter acquisition.

## 📋 Project Description

This project analyzes Twitter behavior across three datasets: Elon Musk’s tweets, Kanye West’s tweets, and Russian bot accounts.  
It explores posting frequency, activity patterns, sentiment, and differences before and after Elon Musk’s Twitter acquisition (April 14, 2022).  
The analysis combines data wrangling, text preprocessing, and exploratory data analysis to compare real accounts versus bot networks.

---

## 📦 Datasets Used

| Dataset | Description |
|--------|-------------|
| Elon Musk Tweets | Full archive of Elon Musk’s tweets |
| Kanye West Tweets | Sampled tweets from Kanye West’s account |
| Russian IRA Bot Tweets | Public dataset of tweets from known bot accounts |

*Datasets were cleaned and harmonized for consistent analysis.*

---

## 🛠️ Methodology

### 1. Data Loading
- Imported datasets from Google Drive into Pandas DataFrames
- Standardized column names (e.g., `content`, `createdAt`)

### 2. Preprocessing
- Converted timestamps into datetime objects
- Split Elon Musk's tweets into "before" and "after" April 14, 2022

### 3. Analysis
- Exploratory Data Analysis (EDA) on tweet counts and posting frequency
- Sentiment analysis and text preprocessing (expected if extended)
- Comparison between real-user patterns and bot account behavior

---

## 💻 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/twitter-social-media-behavior-analysis.git
cd twitter-social-media-behavior-analysis

