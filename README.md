# Webscraping-movies-from-metacritic-with-bs4
The goal of this project was to scrape the web for IMDB and metacritic ratings for a broad category of movies and examine the ratings distribution.

This repository included the working jupyter notebook as well as a saved .csv of the data in a cleaned dataframe.

# Results
Data was scraped successfully for 3612 movies between 2000 and 2020 via BeautifulSoup4. Both metacritic and IMDB ratings were available, along with number of votes for metacritic.

Data was cleaned, and the IMBD ratings were normalized for comparison.

IMDB ratings tend to have a heavy central tendency around 71%, with a std of 7.3

Metacritic ratings tend to have a more widely distributed score with a mean of 63%, and a std of 15.6. Metacritic ratings also shows relatively few ratings in the areas of 50% and 75%. Perhaps this is due to a tendency to avoid round quartile scores.

It was 

# Acknowledgements

Data was sourced from https://www.imdb.com/
  
