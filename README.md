# 🎬 Movie Recommendation System

This is a **Content-Based Movie Recommendation System** built with Python, Pandas, Scikit-learn, and NLTK.  
It recommends movies similar to a given movie using **Cosine Similarity** on textual metadata such as genres, cast, crew, and keywords.

---

## 🚀 Features
- Uses **TMDB 5000 Movies Dataset**
- Text preprocessing:
  - Extracted **genres, keywords, top 3 cast members, director**
  - Cleaned and stemmed words
  - Removed stopwords
- **Bag-of-Words model** with CountVectorizer
- **Cosine similarity** to find most similar movies
- Pickled model for later use
- Ready-to-use **Flask/Streamlit app**
