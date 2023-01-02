# Movie Recommendation Systems - NTU CZ1115: Intro to Data Science and Artificial Intelligence

## Used datasets:
- 27K Movie dataset from [TMDb API](https://developers.themoviedb.org/3/getting-started/introduction)
- 5M Rating dataset from [Movilens](https://grouplens.org/datasets/movielens/) 

## Implemented models:
1. `Content-based Recommender`: Use TF-IDF and Vector Space Model from `scikit-learn` libary.
2. `Collaborative Filtering Recommender`: Use SVD model from `Surprise`, a Python scikit for recommender systems.
3. `Hybrid-based Recommender`: Combine the above two approaches.

All of the insights data analysis and evaluation of the advantages and disadvantages for each model are noted in `Experiments.ipynb`
