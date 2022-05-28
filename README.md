# Analysis of Successful Movies
 Elements of successful movies are analyzed and recommended

## Notebook 1
The notebook [analysis-of-successful-movies-1](analysis-of-successful-movies-1.ipynb) retrieves data from IMDb and reduces the data set for this project to meet the following criteria:
* Exclude any movie with missing values for genre or runtime
* Include only full-length movies (titleType = "movie").
* Include only fictional movies (not from documentary genre)
* Include only movies that were released 2000 - 2021 (include 2000 and 2021)
* Include only movies that were released in the United States

The resulting data sets are then saved as compressed csv files (extension .csv.gz) in the Data folder.
