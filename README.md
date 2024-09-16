# Movie_recommender_system
Welcome to the Movie Recommender System! This project is a simple and intuitive movie recommendation engine, similar to Netflix, that provides personalized movie suggestions based on content similarity.

Features
Content-Based Filtering: The system recommends movies based on the similarity of content (like plot, genre, etc.).
Interactive User Interface: The interface is built using Streamlit, making it easy to interact with the system and select movies.
Poster Display: The system fetches movie posters using the TMDB API and displays them alongside the movie recommendations.
Fast Recommendations: The app is optimized to provide quick recommendations based on the selected movie.

How It Works
Content-Based Filtering: This technique is used to recommend movies that are similar to a selected movie. The system uses a precomputed similarity matrix, which measures the closeness between different movies based on their content features.

Movie Selection: The user selects a movie from the dropdown menu, and the system fetches and displays five similar movies along with their posters.

TMDB API: The app integrates with the TMDB API to fetch movie posters and additional movie details.

Technologies Used
Python
Streamlit
TMDB API
Pandas: For data manipulation and handling movie data.
Pickle: For saving and loading precomputed data structures like the similarity matrix.
