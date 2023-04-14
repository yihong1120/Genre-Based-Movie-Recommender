# Genre-Based Movie Recommender

An intuitive movie recommendation system leveraging genre similarity with TF-IDF and cosine similarity for a personalized film discovery experience.

## Getting Started

These instructions will help you set up the movie recommendation system on your local machine.

### Prerequisites

Ensure that you have the following installed on your machine:

- Python 3.6 or later
- pandas
- scikit-learn
- numpy

You can install the required packages using pip:

```sh
pip install -r requirements.txt
```

### Installing

1. Clone this repository to your local machine:

```sh
git clone https://github.com/yourusername/GenreBasedMovieRecommender.git
```

2. Change to the repository directory:

```sh
cd GenreBasedMovieRecommender
```

3. Download the movie dataset from MovieLens and save it in the dataset/ml-latest-small/ directory.

4. Make sure the dataset file is named movies.csv.

## Usage

1. Open the movie_recommender.py file and modify the following lines with the appropriate movie title and year:

```python
year = 1995
movie_title = "Toy Story"
```

2. Save the changes and run the script:

```sh
python movie_recommender.py
```

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your fork.
4. Create a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

* MovieLens for providing the movie dataset.
