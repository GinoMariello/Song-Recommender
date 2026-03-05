# Song Recommender

> 🚧 **In Progress** — Currently under active development.

A music recommendation system that suggests songs based on tone, tempo, genre, and content. Built with Python, the Spotify API, and SQL, with a machine learning upgrade using scikit-learn.

## Planned Features

- Pull song data from the Spotify API including audio features such as tempo, energy, valence, danceability, and genre
- Store song data in a structured SQL database
- Accept user input for mood, genre, and tempo preferences and return matching songs
- Upgrade matching logic from simple SQL filtering to ML-based recommendations using cosine similarity or K-Nearest Neighbors (KNN)

## Planned Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Core application logic |
| Spotify API (Spotipy) | Pulling song data and audio features |
| SQLite | Storing and querying song data |
| Pandas | Data manipulation and preprocessing |
| scikit-learn | ML-based recommendation logic |

## How It Will Work

1. **Data Collection** — Pull songs and their audio features from the Spotify API and store them in a SQL database
2. **User Input** — User specifies preferences such as mood, genre, and tempo range
3. **Basic Filtering** — SQL queries return songs matching the user's preferences
4. **ML Upgrade** — Cosine similarity compares the user's preference vector against all songs in the database to return the closest matches

## Author

Gino Mariello
