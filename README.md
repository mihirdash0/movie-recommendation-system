# movie-recommendation-system

A machine learning-based Movie Recommendation System built using Python. This system suggests movies to users based on their preferences using content-based filtering and natural language processing techniques.

🚀 Features
📌 Content-based recommendation using movie metadata (genre, overview, tags, etc.)

🧠 NLP techniques like stemming and vectorization (TF-IDF/CountVectorizer)

🎯 Cosine similarity for finding similar movies

🖥️ Simple command-line interface (optional: Flask web interface)

Data Preprocessing: Clean and merge metadata like genres, overview, keywords, etc.

Text Processing: Apply stemming and create a 'tags' column for better similarity detection.

Vectorization: Convert text to vectors using CountVectorizer or TF-IDF.

Similarity Calculation: Use cosine similarity to find movies with similar content.

Recommendation: Input a movie name and get top 5 similar movie suggestions.
