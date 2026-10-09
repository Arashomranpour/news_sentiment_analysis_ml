<div align="center">

# 📰📈 News Headlines → Stock Market Direction

**Can the day's top news headlines predict whether the Dow Jones index goes up or down? A text-classification experiment.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Colab](https://img.shields.io/badge/Open_in-Colab-F9AB00?logo=googlecolab&logoColor=white)

</div>

---

## ✨ Overview

`news_analyze.ipynb` uses `Combined_News_DJIA.csv` - the top 25 daily news headlines with a label for the market's movement:

1. 🧹 Combine and clean the headlines for each day.
2. 🔢 Convert the text to numeric features.
3. 🤖 Train **Random Forest** and **Gradient Boosting** classifiers.
4. 📊 Evaluate with precision / recall / F1 - about **83 % accuracy** on the test split (378 days).

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Arashomranpour/news_sentiment_analysis_ml/blob/main/news_analyze.ipynb)

> ⚠️ Research / learning project - not trading advice.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/news_sentiment_analysis_ml.git
cd news_sentiment_analysis_ml
pip install pandas numpy scikit-learn jupyter
jupyter notebook news_analyze.ipynb
```

Download `Combined_News_DJIA.csv` (Kaggle: *Stock Sentiment / Daily News for Stock Market Prediction*) and put it next to the notebook.

## 📁 Project Structure

```
.
└── news_analyze.ipynb
```

## 🛠️ Tech Stack

`scikit-learn` · `pandas` · `NumPy`
