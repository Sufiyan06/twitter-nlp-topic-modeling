# 📝 Twitter Topic Modeling with LDA & NLP

This project applies **Natural Language Processing (NLP)** and **Latent Dirichlet Allocation (LDA)** to analyze Twitter data and automatically uncover meaningful topics.  
It demonstrates an end-to-end pipeline including data cleaning, text preprocessing, topic modeling, evaluation, visualization, and sentiment analysis.

## 📌 What the Project Does
- Cleans and preprocesses raw tweets (removes URLs, mentions, stopwords, applies lemmatization).
- Creates Bag-of-Words and TF-IDF features for text representation.
- Uses **LDA (Latent Dirichlet Allocation)** for topic modeling, with **coherence score** optimization.
- Assigns each tweet to its **dominant topic** with interpretable keywords.
- Evaluates topic quality using **coherence metrics**.
- Visualizes topics with **pyLDAvis**, word clouds, bar charts, and time trends.
- Analyzes **sentiment per topic** using VADER.

## ⚡ How to Run It
1. Clone this repository or download the notebook:
   ```bash
   git clone https://github.com/YOUR_USERNAME/twitter-nlp-topic-modeling.git
   
2. Install required Python libraries:
pip install pandas numpy nltk spacy gensim pyLDAvis matplotlib seaborn
(Also run python -m spacy download en_core_web_sm if not already installed)

3. Open the notebook:
jupyter notebook tweets_analysis.ipynb

4. Run all cells to:
-Clean the tweets
-Generate features (BoW + TF-IDF)
-Train and evaluate the LDA model
-Visualize topics (pyLDAvis, word clouds, trends, heatmaps)
-Analyze sentiment per topic
(Make sure you have a dataset named twitter_dataset.csv in the same folder.)

## 🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, NLTK, spaCy, Gensim, pyLDAvis, Matplotlib, Seaborn, VADER
Machine Learning: LDA Topic Modeling, Coherence Score Evaluation

## 📂 Output
-Bar chart showing number of tweets per topic
-Line chart showing topic prevalence over time
-Heatmap of topic frequency by month
-Word cloud for each topic
-Interactive pyLDAvis visualization
-Bar chart showing average sentiment score per topic
-CSV file (sample_tweets_per_topic.csv) with dominant topic labels for each tweet

## 🚀 Future Improvements
-Real-time topic detection using the Twitter API
-Integration with a dashboard (Streamlit/Plotly)
-Combining LDA with sentiment trends for deeper insights
👉 Replace `YOUR_USERNAME` in the clone link with your actual GitHub username.  
