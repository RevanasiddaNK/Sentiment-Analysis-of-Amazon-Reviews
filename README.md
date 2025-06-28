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


2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the Jupyter notebook or run the Python script.

```bash
jupyter notebook SentimentAnalysis.ipynb
```

> ⚠️ Make sure you download the `amazon.csv` dataset and place it in the root directory.

## 📈 Results

Top 5 positive reviews based on Wilson Lower Bound Score:

| Reviewer Name        | Polarity | Subjectivity | Sentiment |
| -------------------- | -------- | ------------ | --------- |
| Hyoun Kim "Faluzure" | 0.16     | 0.56         | Positive  |
| NLee the Engineer    | 0.10     | 0.52         | Positive  |
| SkincareCEO          | 0.21     | 0.50         | Positive  |
| Amazon Customer      | 0.14     | 0.49         | Positive  |
| Twister              | 0.17     | 0.51         | Positive  |

## 📷 Visuals

* Sentiment distribution via bar and pie charts
* Overall rating distribution
* Word clouds for common words in reviews (can be added as enhancement)

## ✅ To Do

* Add word cloud visualizations
* Use machine learning models like Logistic Regression or Naive Bayes
* Create a web app using Streamlit or Flask

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve this project.

## 📜 License

This project is licensed under the MIT License.

---
