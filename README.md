# Movie Recommendation System

A content-based Movie Recommendation System built using Machine Learning techniques to provide personalized movie suggestions based on movie metadata. The application leverages TF-IDF vectorization and cosine similarity to recommend movies with similar content and is deployed as an interactive web application using Streamlit.

## Live Demo

🔗 https://lnkd.in/gBV4sqdc

## Features

* Personalized movie recommendations
* Content-based filtering using TF-IDF
* Fast similarity search using cosine similarity
* Interactive Streamlit web interface
* Real-time movie search and recommendations
* Deployed for public access

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* TF-IDF Vectorization
* Cosine Similarity

## Project Structure

```bash
movie_recommendation/
│
├── app.py                    # Streamlit application
├── main.py                   # Core recommendation logic
├── movies_metadata.csv       # Dataset
├── tfidf.pkl                 # Saved TF-IDF vectorizer
├── tfidf_matrix.pkl          # TF-IDF matrix
├── indices.pkl               # Movie indices mapping
├── df.pkl                    # Processed dataset
├── requirements.txt          # Dependencies
└── movie_recommendation.ipynb # Development notebook
```

## How It Works

1. Preprocess movie metadata and extract relevant features.
2. Convert textual information into numerical vectors using TF-IDF.
3. Compute cosine similarity between movies.
4. Retrieve and rank the most similar movies.
5. Display recommendations through the Streamlit interface.

## Installation

### Clone the Repository

```bash
git clone <repository_url>
cd movie_recommendation
```

### Create Virtual Environment

```bash
python -m venv .venv
```

Activate the environment:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/Mac**

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

## Future Improvements

* Hybrid recommendation system
* Collaborative filtering integration
* User authentication
* Movie posters and trailers
* Personalized user profiles

## Author

**Parmpreet Kaur**

Passionate about Artificial Intelligence, Machine Learning, and Generative AI.
