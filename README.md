# 🛍️ Sentiment Analysis of Amazon Reviews

This project performs **sentiment analysis** on Amazon product reviews using **VADER** and **TextBlob**. It includes data cleaning, exploratory data analysis (EDA), and visualizations to understand how users feel about different products.

## 🔍 Features

- Data preprocessing & cleaning
- Missing values and class analysis
- Text cleaning & normalization
- Sentiment classification using:
  - **TextBlob** (polarity and subjectivity)
  - **VADER Sentiment Analyzer**
- Visualization of sentiment distribution
- Top positive reviews based on **Wilson Lower Bound Score**
- Categorical summary with bar and pie charts

## 📊 Sample Output

- Countplot and Pie chart for `overall` and `sentiment`
- Polarity and subjectivity scores added to each review
- Reviews tagged as Positive, Negative, or Neutral
- Top 5 most helpful positive reviews

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly, Cufflinks
- NLTK, VADER, TextBlob
- WordCloud

## 📁 Dataset

The dataset used is `amazon.csv` and includes the following columns:
- `reviewerName`, `overall`, `reviewText`, `reviewTime`
- `helpful_yes`, `helpful_no`, `score_average_rating`
- `wilson_lower_bound` (precomputed helpfulness score)

## 🧪 Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Sentiment-Analysis-of-Amazon-Reviews.git
cd Sentiment-Analysis-of-Amazon-Reviews
