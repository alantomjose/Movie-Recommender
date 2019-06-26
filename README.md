# Movie-Recommendeder
A ML project that reccommends you personalised movie reccommendations based on movies you like.This finds movies similar to a movie that you lika on grounds on cast, director, tags and description.
The directors name is giver weightage of 3 while cast and tags are given a weightage of 1. This uses TF-IDF Vectoriser to find similarities and make a cosine similarity matrix to reccommend movies, afterwhich it is sorted by weighted rating(IMDB's rating formulae) to put popular movies on top. Earlier version used overview and description to find similarity matrix which was found to be less appealing.

## Usage
Run 'Movie_reccomender.ipynb' in ipython notebook , preferably jupyter notebook. Then run the function with the name of the movie you wish like as in the example to get your reccomendations. 

## Disclaimer
- Due to limitations in RAM , only top ~22,000 movies(with rating above 6.5) are considered in the list.
- Due to github's policy on file size the original csv files are not uploaded.The needed files are made and uploaded herewith.
- The original file used to develop this model is in 'MovieRecFull.ipynb'. The files imported in the file are not include due to size constraints. 
