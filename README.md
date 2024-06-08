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

Tableau (Public) Link:


**Methods**

we are trying to predict Streams and if the song made it to spotify’s charts and where it charted.
First we decided to remove all of the variables that was not a
Float or integer.
Converted the streams from object to int64.

First, we tried to use **Linear Regression** to find if there's 
relation between streams/charts (dependant variable) to all 
the other variables (independent variables).

then we use the model, **Random Forest**  that is the “opposite” to linear regression and is robust 
against non-linear data to see if there is any improvement.

**Results**

Overall - Both of them are not great but random forest is slightly better, this is backed up 
by how accurate the mode “thinks” it is using the score method on the test data.
Streams: 97% Random Forest, 65% Linear Regression
Charts: 90% Random Forest, 6% Linear Regression
While Random Forest is closer to the actual value in magnitude, it tends to
cluster its predicted number and does not deviate much

**Visualization**

We use Tableau and Seaborn





/

**Conclusions and Recomendations**

•Include Artist Name for modeling & predictions to be likely more accurate

•Further understanding on Spotify % of

    Danceability %
   
    Valence %
   
    Energy %
   
    Acousticness %
   
    Instrumentalness %
   
    Liveness %
   
    Speechiness %
   
•Track YoY changes in statistics for developing further modeling & identifying YoY trendsJ

•Knowing the length of the song will add the to model’s robustness


Project contributers :

• Bianca Santalla

• Jithu Ann Jacob

• Rob Yaggi

• steve deonarine
 
 










