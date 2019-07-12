# IMDb Scraper in Python for TV Shows
This scraper can be used to generate following data for any TV show on IMDb.

1. Episode Title
2. IMDb Rating
3. Total Votes
4. Air Date


# How to run?

1. Download the repository or clone using ```git clone https://github.com/jainanuj7/IMDb-ratings-scraper.git```

2. Open IMDb.py and edit the ```season_id``` and ```number_of_seasons``` variables <br>
Eg for 'The Office' <br>
IMDb URL: https://www.imdb.com/title/tt0386676/?ref_=ttep_ep_tt <br>
Therefore ```season_id = 'tt0386676'``` and ```number_of_seasons = 10```

3. Run IMDb.py ```python IMDb.py``` <br>
Note: Internet connection will be required while running the script since it fetches live data

4. Output will be generated within same folder

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