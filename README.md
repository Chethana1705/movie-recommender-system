# Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Streamlit**, and **Machine Learning**. This application recommends movies similar to the one selected by the user using cosine similarity.

---

## Overview

This project recommends movies based on their content by comparing features such as genres, cast, crew, keywords, and overview. It uses a precomputed cosine similarity matrix to provide fast and accurate recommendations through a simple Streamlit interface.

---

## Features

- Recommend similar movies instantly
- Content-based recommendation algorithm
- Fast prediction using preprocessed data
- Interactive Streamlit web interface
- Lightweight and easy to deploy

---

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Pickle

---

## Project Structure

```text
movie-recommender-system/
│
├── myapp.py                 # Streamlit application
├── movies.pkl               # Movie dataset
├── movie_dict.pkl           # Processed movie dictionary
├── similarity.pkl           # Cosine similarity matrix
├── requirements.txt         # Required libraries
├── setup.sh                 # Deployment setup
├── Procfile                 # Deployment configuration
├── README.md
└── .gitignore
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Chethana1705/movie-recommender-system.git
```

### Navigate to the project directory

```bash
cd movie-recommender-system
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run myapp.py
```

---

## How It Works

1. Load the processed movie dataset.
2. Select a movie from the dropdown menu.
3. Calculate similarity scores using the precomputed cosine similarity matrix.
4. Display the top recommended movies.

---

## Machine Learning Approach

This project uses a **Content-Based Recommendation System**.

The recommendation engine compares movies based on metadata including:

- Genres
- Keywords
- Cast
- Crew
- Overview

After preprocessing, the features are vectorized and cosine similarity is calculated to recommend the most similar movies.

---

## Dependencies

- Streamlit
- Pandas
- NumPy
- Scikit-learn

Install all required libraries using:

```bash
pip install -r requirements.txt
```

---

## Future Enhancements

- Integrate TMDB API for movie posters
- User authentication
- Hybrid recommendation system
- Collaborative filtering
- Rating prediction
- Search functionality
- Deployment on Streamlit Cloud

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## License

This project is developed for educational and learning purposes.

---

## Author

**Chethana R**

GitHub: https://github.com/Chethana1705

---

If you found this project useful, consider giving it a star on GitHub.
