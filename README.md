# Project-4
**Predicting Music Trends**

The music market is extremely competitive with artists always trying to make the next viral song and get the most streams. For this project, Our group aims to find a way to see if we can develop an algorithm that can give artists a competitive edge. 

 Based on the date it was released, bpm, key, energy, danceability, acoustic-ness and more, we are looking to see if we can predict the following:
 
•How many streams?

•Is it in spotify’s playslists?

•Is it in spotify’s charts?

We plan on utilizing some dataset we found on Kaggle that has all those metrics already. We plan to pick a song, remove it from the dataset and then use that dataset to train a model to predict the streams and other info. This way we have ground truth to compare our results to.


The dataset can be found in the following link:

https://www.kaggle.com/datasets/zeesolver/spotfy

**Methods**

we are trying to predict Streams and if the song made it to spotify’s charts and where it charted.
First we decided to remove all of the variables that was not a
Float or integer.
Converted the streams from object to int64.

First, we tried to use **Linear Regression** to find if there's 
relation between streams/charts (dependant variable) to all 
the other variables (independent variables).




