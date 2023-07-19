# Multi-purpose film data aggregator
Find it on Kaggle: https://www.kaggle.com/datasets/albertobm/film-data-aggregator

Your one-stop shop for comprehensive film data!

Inspired by [The Ultimate Film Statistics Dataset](https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-film-statistics-dataset-for-ml) I decided to make my own film data set. It is based on scraping Letterboxd pages and lists, adding financial and ratings information from IMDb and Metacritic.

Data included:
- Title
- Year
- Release date
- Director
- Writer
- Main cast
- Runtime
- Genre
- Country
- Language
- Budget
- Box office
- IMDb score
- Number of IMDb user votes
- Number of IMDb user reviews
- IMDb URL
- Letterboxd score
- Number of Letterboxd votes
- Number of Letterboxd watches
- Number of Letterboxd reviews
- Letterboxd URL
- Metacritic critic score
- Number of Metacritic critic reviews
- Metacritic user score
- Number of Metacritic user votes
- Number of Metacritic user reviews
- Metacritic URL

The good:
- Works both directly with the database (empty search and sorting by ranking, popularity, etc.), as well as with user-crafted lists.
- Customizable amount of entries to collect.

The not so good:
- This was my first attempt at web scraping so my approach is probably light-years away from efficient. Letterboxd and Metacritic are rather friendly, while IMDb is pain...
- Although Letterboxd allows to filter out some non-film elements (TV shows, shorts), others dodge these filters (comedy specials, music documentaries).
- Financial data is rather basic. It could be expanded using The Numbers or Box Office Mojo.
- Currency conversion rates are hard-coded and inflation is not adjusted for.
- Streaming platforms do not provide budget nor box office data.
