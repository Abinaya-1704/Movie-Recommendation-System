# Movie-Recommendation-System

A machine learning project that uses content-based filtering, NLP techniques, and cosine similarity to recommend movies. This project is implemented in Google Colab for seamless collaboration and execution.

## Features  
- Content-based movie recommendations using movie metadata.  
- NLP techniques to analyze and preprocess movie descriptions.  
- Cosine similarity to measure similarity between movies.  

## Technologies Used  
- **Platform**: Google Colab  
- **Programming Language**: Python  
- **Libraries**:  
  - NumPy  
  - Pandas  
  - Scikit-learn  
  - NLTK (Natural Language Toolkit)  
  - Matplotlib  

## How It Works  
1. **Data Preprocessing**:  
   - Tokenization, stemming, and stop-word removal applied to movie descriptions.  
2. **Feature Extraction**:  
   - TF-IDF vectorization on movie descriptions.  
3. **Similarity Computation**:  
   - Cosine similarity matrix calculated for movie vectors.  
4. **Recommendation**:  
   - Input a movie, and the system recommends the most similar movies.  

## Dataset  
- (/content/movies.csv)  
- Includes metadata like titles, genres, descriptions, and more.

