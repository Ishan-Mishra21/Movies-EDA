# IMDb Movie Data Exploration

EDA performed on an IMDb movies dataset to find insights into movie statistics.

## Dataset

Dataset used is the TMDB 5000 Movies Dataset from Kaggle which can be found at: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Key Findings

1. Budget and revenue have a strong correlation (r = 0.71) but there is almost no correlation between budget and rating (r = -0.01)
2. Older movies (released before 1980) seem to have higher ratings but that is highly affected due to survivorship bias
3. Horror and music movies have some of the lowest budgets but have the highest ROIs
4. Ratings seem to be similar across all months of release but movies released in June and July earn significantly more than movies released in other months

## Tools Used

Libraries: NumPy, Seaborn, Matplotlib, Pandas, json

## How to Run
1. Download the MoviesEDA.ipynb file and open it in Google Colab
2. Add the tmdb_5000_movies.csv file (from the link provided above) in Google Colab's local storage
3. Click on run all cells
