# 📝 Twitter Topic Modeling with NLP & Machine Learning

This project applies Natural Language Processing (NLP) and Machine Learning to analyze Twitter data and automatically group tweets into meaningful topics.  
It demonstrates an end-to-end pipeline including data cleaning, text preprocessing, feature extraction, clustering, evaluation, and visualization.


## 📌 What the Project Does
- Cleans and preprocesses raw tweets (removes URLs, mentions, stopwords, applies lemmatization).
- Converts text into numerical features using **TF-IDF vectorization**.
- Uses **K-Means clustering** to identify hidden topics from tweets.
- Evaluates clustering quality with **Silhouette Score** and **inertia**.
- Visualizes the number of tweets per topic and outputs results to a CSV file.


## ⚡ How to Run It
1. Clone this repository or download the notebook:
   ```bash
   git clone https://github.com/YOUR_USERNAME/twitter-nlp-topic-modeling.git

2.Install required Python libraries:
pip install pandas numpy nltk scikit-learn matplotlib

3.Open the notebook:
jupyter notebook tweets_analysis.ipynb

4. Run all cells to:
-Clean the tweets
-Generate TF-IDF features
-Cluster tweets into topics
-Visualize and export results
(Make sure you have a dataset named twitter_dataset.csv in the same folder.)

## 🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, NLTK, Scikit-learn, Matplotlib
Machine Learning: TF-IDF Vectorizer, K-Means Clustering

## 📂 Output
-Bar chart showing number of tweets per topic.
-Line chart showing topic prevalence over time.
-Heatmap showing topic frequency by month.
-Work cloud for each topic group
-Interactive topic model visualization using pyLDAvis
-Bar chart showing Average Sentiment score per topic
-CSV file (sample_tweets_per_topic.csv) with topic labels for each tweet.

##🚀 Future Improvements
-Real-time topic detection using Twitter API.
-Integration with a dashboard (Streamlit/Plotly).

---

👉 Replace `YOUR_USERNAME` in the clone link with your actual GitHub username.  
