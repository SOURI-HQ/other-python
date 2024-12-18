## 💡 About this project

This is a movie recommendation engine that utilizes the Euclidean and Pearson algorithm to recommend 5 movies to watch
and 5 movies not to watch based off of a given list of movies listed and reviewed by a group of people on the scale
from 0.0 to 10.0.

## 🛠️ Project setup
To run this project make sure that you:
- download at least a 3.10 version of Python
- download and install deep_translator with the following command via the terminal:
`pip install deep_translator`,
- generate an api key from: https://www.omdbapi.com/apikey.aspx and use it in OMDB_API_KEY variable,
- launch the project from your favorite IDE with arguments specifying the user index for which the movies are being
    recommended and the algorithm, for example:
    "0 euclidean", "5 pearson".

The list of reviewed movies by users is fetched from data.csv file.
