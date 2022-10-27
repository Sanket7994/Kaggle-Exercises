About Dataset
-------------------
Subsets of IMDb data are available for access to customers for personal and non-commercial use. You can hold local copies of this data, and it is subject to our terms and conditions. Please refer to the Non-Commercial Licensing and copyright/license and verify compliance.

This Dataset contains all the titles present on IMDB website on or before 7th October 2022. If you need latest, it is present at location IMDB Official Dataset Source

IMDb Dataset Details
---------------------

title.basics.tsv - Contains the following information for titles:
tconst (string) - alphanumeric unique identifier of the title
titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release
originalTitle (string) - original title, in the original language
isAdult (boolean) - 0: non-adult title; 1: adult title
startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year
endYear (YYYY) – TV Series end year. ‘\N’ for all other title types
runtimeMinutes – primary runtime of the title, in minutes
genres (string array) – includes up to three genres associated with the title

title.crew.tsv – Contains the director and writer information for all the titles in IMDb. Fields include:
tconst (string) - alphanumeric unique identifier of the title
directors (array of nconsts) - director(s) of the given title
writers (array of nconsts) – writer(s) of the given title

title.ratings.tsv – Contains the IMDb rating and votes information for titles
tconst (string) - alphanumeric unique identifier of the title
averageRating – weighted average of all the individual user ratings
numVotes - number of votes the title has received


Kaggle Dataset link: https://www.kaggle.com/datasets/riyapatel1697/imdb-official-movies-dataset?select=title-metadata.tsv

My Profile link: https://www.kaggle.com/sanket7994