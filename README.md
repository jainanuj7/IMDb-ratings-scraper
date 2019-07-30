# IMDb Scraper in Python for TV Shows
This scraper can be used to generate following data for any TV show on IMDb.

1. Episode Title
2. IMDb Rating
3. Total Votes
4. Air Date


# How to run?

1. Download the repository or clone using ```git clone https://github.com/jainanuj7/IMDb-ratings-scraper.git```
2. Sample usage of ```IMDB_Web_Scrape``` class:
```
# Create an obejct of IMDB_Web_Scrape class and pass IMDb tv show id and number of shows
# Eg creating obejct for The Office (US) https://www.imdb.com/title/tt0386676/
TVShow = IMDB_Web_Scrape("tt0386676", 9)

# pull_seasons() returns the resultant pandas dataframe
dataset = TVShow.pull_seasons()

# Write dataset to csv
dataset.to_csv("results.csv")

```

# Why was this scraper developed?
Till date, IMDb doesn't have official APIs.
Yes, there are many sophisticated solutions like TMDb and OMDb but, <br>
1. OMDb is not free anymore, API key is required. API key in free tier has limited number of calls. And the premium API key.. WAIT, Who wants to pay for a personal project anyway?
2. TMDb is a whole new database with no connection to IMDb.
3. IMDb has some official dumps of all tv shows/movies, I wasn't able to find ratings in them. Also, nothing is mentioned regarding the when were the datasets last updated. Check out the official datasets at: https://www.imdb.com/interfaces/

# Improvements in the scraper
Let me know in the 'Issues' section how this scraper can be futher improved. <br>

### Office Fan? 🐻
Check out my Data Analysis of The Office (US) at https://github.com/jainanuj7/bears-beets-battlestar-analytica
