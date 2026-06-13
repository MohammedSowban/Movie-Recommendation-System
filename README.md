# Movie-Recommendation-System
The Movie Recommendation System is a Machine Learning project that recommends movies to users based on movie information such as genres, overview, ratings, language, popularity, and other metadata.

The system analyzes movie features and suggests similar movies using content-based filtering techniques, helping users discover movies that match their interests.

Features
- Movie recommendation based on similarity
- Content-Based Filtering approach
- Uses movie metadata and descriptions
- Recommends top similar movies instantly
- Handles large movie datasets efficiently
- Easy-to-use and customizable

##  Dataset Information

The dataset contains movie metadata collected from thousands of movies.

Dataset Columns
Column	Description
- adult	Indicates whether the movie is for adults
- belongs_to_collection	Movie collection information
- budget	Production budget of the movie
- genres	Movie genres
- homepage	Official movie website
- id	Unique movie ID
- imdb_id	IMDb identifier
- original_language	Original language of the movie
- original_title	Original movie title
- overview	Movie description/summary
- popularity	Popularity score
- poster_path	Movie poster path
- production_companies	Production companies
- production_countries	Production countries
- release_date	Release date
- revenue	Revenue generated
- runtime	Duration of the movie
- spoken_languages	Languages spoken
- status	Release status
- tagline	Movie tagline
- title	Movie title
- vote_average	Average rating
- vote_count	Number of votes
- Dataset Size
- Total Records: ~45,000 Movies
- Features: 24+ Columns
- File Format: CSV

## 🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
NLTK
Matplotlib
Seaborn
Jupyter Notebook

## Project Workflow
1. Data Collection
Load movie dataset
Inspect data structure
Understand movie attributes
2. Data Preprocessing
Handle missing values
Remove duplicate entries
Clean text features
Convert genres into usable format
3. Feature Engineering

Combine important columns:

Genres
Overview
Keywords
Cast
Crew

Create a unified text representation for each movie.

4. Vectorization

Use:

CountVectorizer
TF-IDF Vectorizer

to convert text data into numerical vectors.

5. Similarity Calculation

Calculate similarity using:

Cosine Similarity

Generate similarity scores between movies.

6. Recommendation Generation

When a user selects a movie:

- Find its vector representation.
- Calculate similarity with other movies.
- Sort movies by similarity score.
- Return Top Recommended Movies.

## Machine Learning Technique
Content-Based Filtering

The recommendation system suggests movies based on movie characteristics rather than user ratings.

Advantages:

- No user history required
- Fast recommendations
- Personalized suggestions
- Easy to interpret

## Evaluation

The recommendation quality is evaluated using:

* Cosine Similarity Scores
* Relevance of Recommended Movies
* User Satisfaction
* Recommendation Diversity
## Image

## Author

Mohammed Sowban

Electronics and Communication Engineering (ECE) Student
Data Science & Machine Learning Enthusiast
