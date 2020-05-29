# Project3-Anime
![](images/dataset-cover.png)

Project3-Anime Database

For my third project in Flatiron I wanted to use a dataset I really was interested in. I chose to do my project on anime. Specifically  data on anime from myAnimelist.net. I used a .csv file from kaggle.com the had data from myAnimeList.net. I had to drop more then half of the dataset because it was mainly hentai and I'm not interested in that for this project. Maybe later... but seriously from 14,478 to 5,561 unique anime data points and a few entries that were not usable.

## What Did I Do?

* Imported .cvs file

* Cleaned .csv file and removed all hentai.

* Created Dummies variables for non-numerical data (for columns : Type, Source, Rating) so we can work with these data.

* Visualized all data against each other to see if we can find any solid correlations

![](images/pairplotAnime.csv.jpg)

* Found correlations between each category.

![](images/Corr.heatmap.png)

* I then played around with training models (Linear,Logistic,Ridge, Lasso and Knn Regressions)

Total # of Scores against Total # of Members of an Anime
![](images/membersvscored_by_reg.png)

Rank against Score of an Anime
![](images/rankvscore_reg.png)


## Built With

* Python3.8
* Jupyter Notebook 6.0.0
* A few imports: pandas, numpy, matplotlib.pyplot, seaborn, statsmodels and sklearn


## Authors

* **Samuel Diaz** - *Creator* - [sdman135](https://github.com/sdman135/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Azathoth - https://www.kaggle.com/azathoth42/myanimelist (the initial .csv file I used, had to clean heavily though...)
* codebacis - https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ
