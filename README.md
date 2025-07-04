# prodigy_task4
4 Twitter Sentiment Analysis
Task‑04‑Twitter‑Sentiment‑Analysis/README.md

# Task 04 – Sentiment Patterns in Twitter Data

Analyze entity‑level sentiment in tweets to understand public opinion about brands, products, or topics.

## 📂 Dataset  
Kaggle: **[Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)**  
Contains tweet text, entity, sentiment label, and confidence.

## 🎯 Workflow  
1. **Text Pre‑processing** – lowercase, emoji removal, URLs, stop‑words, stemming.  
2. **Tokenization & Vectorization** – TF‑IDF (baseline) + optional BERT embeddings.  
3. **Exploratory Visuals**  
   * Frequency of entities (bar chart).  
   * Word cloud for positive vs. negative tweets.  
   * Time‑series of sentiment proportions (if timestamp available).  
4. **Modeling** – Baseline logistic regression; compare with fine‑tuned DistilBERT.  
5. **Dash / Streamlit Demo (optional)** – Interactive sentiment dashboard.
