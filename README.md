# 🧠 Employee Sentiment Analysis – AI Project

This project evaluates employee sentiment and engagement by analyzing email messages using natural language processing and data science techniques. It includes sentiment labeling, exploratory analysis, risk identification, and predictive modeling using Python and open-source libraries.

---

## 📂 Dataset

- **File:** `test.csv`
- **Fields:** `Subject`, `body`, `date`, `from`
- **Total Entries:** 2,191 email records

---

## 🎯 Project Objectives

1. **Sentiment Labeling**: Tag messages as **Positive**, **Negative**, or **Neutral** using TextBlob/VADER NLP tools.
2. **Exploratory Data Analysis (EDA)**: Visualize sentiment distribution, trends over time, and anomalies.
3. **Employee Score Calculation**: Assign and aggregate sentiment scores monthly for each employee.
4. **Employee Ranking**: Identify top 3 positive and top 3 negative employees per month.
5. **Flight Risk Detection**: Flag employees with 4+ negative messages in any rolling 30-day window.
6. **Predictive Modeling**: Train a linear regression model to forecast sentiment score trends.

---

## 🧰 Tools & Libraries

- **Python** (v3.x)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `TextBlob` or `vaderSentiment`
- `scikit-learn`

---

## 📊 Visualizations

- Bar chart of sentiment labels
- Line plot of sentiment trends over months
- Employee ranking tables
- Model evaluation metrics

---

## 📈 Model Overview

- **Model**: Linear Regression
- **Features**: Monthly message count, time
- **Target**: Monthly sentiment score
- **Metrics**: R² Score, Mean Squared Error

---

## 📝 How to Run

1. Clone the repo and install dependencies:
   ```bash
   pip install -r requirements.txt
