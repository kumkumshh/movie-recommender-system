
# Movie Recommender System

This repository contains the code for a movie recommender system built using machine learning. The system recommends movies based on user preferences and uses cosine similarity for recommendations.

## Features
- **Movie Recommendation**: Recommends movies similar to the one selected by the user.
- **Cosine Similarity**: Uses cosine similarity to measure how closely related movies are based on their features.
- **Python & Streamlit**: The app is developed using Python and deployed with Streamlit.

## Repository Structure
- **app.py**: The main application file that runs the recommender system.
- **movies.pkl**: A pickle file containing the movie data.
- **movies_dict.pkl**: A dictionary of movie details used for the recommendation process.
- **similarity.pkl**: A pickle file that stores the precomputed similarity matrix between movies.
- **requirements.txt**: A list of dependencies needed to run the application.
- **setup.sh**: Shell script to help set up the environment for deployment.
- **.gitattributes**: Tracks large files like `.pkl` files using Git LFS.

## Getting Started

### Prerequisites
- Python 3.x
- pip (Python package installer)
- Streamlit (for running the web app)

### How it Works
- The system recommends movies based on the cosine similarity of movie features.
- Users can input or select a movie, and the system will return a list of recommended movies.

## Technologies Used
- **Python**: For data processing and building the recommendation engine.
- **Streamlit**: To create a user-friendly interface for the web app.
- **Pickle**: Used to save the preprocessed data and similarity matrix.
- **Git LFS**: For tracking large files like `.pkl` files.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
