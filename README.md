# About this Project

Extract data from Ghibli movie database, preprocess the data, and perform sentiment analysis to predict if the movie is negative, positive, or neutral

![image](https://image.tmdb.org/t/p/w185_and_h278_bestv2/hnYowHwLq0iUWriAHtiiCWsI2dP.jpg)

# Data Source
Extract data from [Movie Database](https://www.themoviedb.org/list/4309/)

# Notebook and Article
Access the notebook of this project [here](https://github.com/khuyentran1401/Web-scrape-Ghibli-Movie-Database/blob/master/Web%20scrape%20Ghibli%20Movie%20DB-3.ipynb) and the tutorial article [here](https://medium.com/analytics-vidhya/detailed-tutorials-for-beginners-web-scrap-movie-database-from-multiple-pages-with-beautiful-soup-5836828d23?source=friends_link&sk=e9de6368353d703275ec4555b0ebdd0d)

# Tools
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): a Python library for pulling data out of HTML and XML files.
* Numpy, Pandas: tool to read and preprocess data
* [NLTK (Natural Language Processing Toolkit)](https://www.nltk.org/): tool to preprocess text
* Scikit-learn: tool to perform sentiment analysis

# Techniques
1. Scrape movie database with BeautifulSoup
  * Extract title, url, image, rank, and rating
2. Preprocess data
  * Put data into a dataframe
  * Convert string into numerical values
  * Transform categorical variables (movie categories) into binary
3. Preprocess text with NLTK
  * Remove punctuations and stopwords
  * Lematize words
4. Perform sentiment analysis with CountVectorizer

# Result
**Accuracy**: 0.6049
