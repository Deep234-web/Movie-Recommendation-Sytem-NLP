# Movie Recommendation System

## Overview

This project is a Movie Recommender System deployed on Heroku using Streamlit for a user-friendly interface. The system provides movie recommendations based on user input, showcasing the recommended movies along with their posters.

## Features

- **Movie Selection**: Users can select a movie from a dropdown list.
- **Recommendations**: The app provides a list of recommended movies similar to the selected movie.
- **Visuals**: Each recommendation includes a movie poster for better visualization.

## How It Works

1. **Data Loading**: Movie data and similarity metrics are loaded from pre-saved pickle files.
2. **Recommendation**: The system uses a similarity matrix to find and recommend movies similar to the user's selection.
3. **Poster Fetching**: The app fetches movie posters from The Movie Database (TMDb) API to enhance user experience.

## Setup Instructions

### Prerequisites

- Python 3.x
- Streamlit
- Pandas
- Requests
- Pickle

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system

2. Install the required packages:
  pip install streamlit pandas requests

**Note:** The `movie_dict.pkl` and `similarity.pkl` files are not included in this repository due to their large size. Please run the notebook provided in this repository to generate these pickle files.

## Deployment

This app is deployed on Heroku. You can access it through the following link:

[Movie Recommender System on Heroku](https://movie-recommendor-system-2f3b3aab88f4.herokuapp.com/)


## What I Learned
Through this project, I gained valuable experience in deploying a Python web application using Heroku and Streamlit. I learned to integrate machine learning models into web applications and effectively manage external API requests. The use of CountVectorizer for feature extraction and the extensive feature engineering performed were crucial in developing a robust recommendation system. This project also enhanced my skills in managing and deploying data-driven applications in a cloud environment.

## Contributing
Feel free to fork the repository, create a branch, and submit a pull request. Any improvements or bug fixes are welcome!
