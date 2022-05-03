# HitMusic
Chloe Woodcock
chloeanne2559@gmail.com
University Individual Final Project
Looking at whether lyrics and tweets can be used to predict a hit song. I used an initial dataset downloaded off Kaggle.com names 'charts.csv', and then used the Genius API to collect lyrics and the Spotify API to collect release dates, popularity score and lyric explicitness. Finally uses the Twitter API to scrap associated tweets pre- and post-release date. A lot of manual importing and finding of lyrics and release dates was necessary, and I manually checked all APIs collected the correct data. Then used Cross Validation Grid Search to find optimal parameters for Logisitic Regression, Support Vector Machine and Random Forest classifiers.
