# Twitter-Sentiment-Analysis
Twitter Entity Sentiment Analysis using Machine Learning A comprehensive NLP pipeline that classifies sentiments (Positive, Negative, Neutral, Irrelevant) for specific entities mentioned in tweets. Built using Python, Scikit-Learn, and TF-IDF vectorization, featuring an interactive UI for real-time predictions.

To make your project professional and easy for others (like recruiters or other developers) to understand, you should use a **README.md** file. This is the "face" of your project on GitHub.

Below is a template specifically tailored to the **Twitter Entity Sentiment Analysis** project we just built.

# 🐦 Twitter Entity Sentiment Analysis

This project implements a machine learning pipeline to analyze the sentiment of tweets toward specific entities (brands, games, or companies). Unlike standard sentiment analysis, this model focuses on the context of a particular entity within the tweet.

## 🚀 Features
* **Data Preprocessing**: Comprehensive cleaning (URLs, mentions, punctuation removal) and handling of missing values.
* **Feature Engineering**: 
    * **Text**: TF-IDF Vectorization to convert tweets into numerical features.
    * **Entities**: One-Hot Encoding and Feature Scaling for categorical brand data.
* **Multiple Models**: Comparison between Logistic Regression, Decision Trees, and Random Forest.
* **Interactive UI**: A built-in interface (using `ipywidgets`) to test real-world tweets instantly.



## 📊 Dataset
The project uses the **Twitter Entity Sentiment Analysis** dataset, which consists of:
* `twitter_training.csv`: 74,000+ labeled tweets.
* `twitter_validation.csv`: 1,000 labeled tweets for testing.
* **Labels**: Positive, Negative, Neutral, Irrelevant.

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment**: Google Colab / Jupyter Notebook

## 📈 Performance
The models were evaluated based on **Training and Testing Accuracy**.
* **Logistic Regression**: Excellent balance of speed and accuracy.
* **Random Forest**: Highest overall accuracy for complex sentiment patterns.

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/twitter-sentiment-analysis.git](https://github.com/YOUR_USERNAME/twitter-sentiment-analysis.git)

```

2. Install dependencies:
```bash
pip install pandas scikit-learn matplotlib seaborn joblib

```


3. Open the Jupyter Notebook and run the cells to train the model and launch the interactive UI.

## 🔮 Inference Example

```python
# Test a real tweet
tweet = "I love the new graphics update for Nvidia cards!"
entity = "Nvidia"
print(predict_sentiment(tweet, entity)) 
# Output: Positive

```

```


2.  **Upload the `sentiment_model.pkl`**: (Optional) This allows others to use your trained model without re-training.
3.  **Add a Screenshot**: Take a screenshot of your **UI results** or the **Confusion Matrix** plot and include it in your README. It makes the project look much more impressive!

**Would you like me to help you write a summary of the findings (Conclusion) to add to the bottom of this README?**

```
