
# Movie Recommender System

Welcome to the Movie Recommender System repository! This system helps you discover new movies based on your preferences. It uses advanced algorithms to analyze movie features and suggest similar ones you might enjoy.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Algorithms Used](#algorithms-used)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Movie Recommender System is designed to make movie suggestions tailored to your tastes. Whether you love action, drama, or comedy, this system has got you covered. It utilizes advanced techniques to understand the features of movies and recommends ones that closely match your preferences.

## Usage

To use the Movie Recommender System, follow these simple steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Yampss/recommendersys.git
   cd recommendersys
   ```


## Algorithms Used

- **Cosine Similarity Function:**
  - Measures how similar two movies are based on their features (genres, ratings).
  - Helps in suggesting movies that are closely related to your preferences.

- **Count Vectorizer:**
  - Converts movie descriptions or reviews into numbers for analysis.
  - Considers the actual words people use, enhancing the accuracy of recommendations.

- **Port Stemmer Function:**
  - Simplifies words by removing endings.
  - Improves the system's understanding of words, making recommendations more accurate.

## Installation

1. Clone the repository.
2. Run the recommender using `python movierecommender.py`.

**Note:** Ensure you have the required datasets from TMDb Movie Ratings on Kaggle (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv).

## Contributing

If you have ideas for improvements or new features, feel free to open an issue or submit a pull request. Your contributions are always welcome!

## License

This project is licensed under the [MIT License](LICENSE).

---


