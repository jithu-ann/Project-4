# Project-4
## **Predicting Music Trends**

The music market is extremely competitive with artists always trying to make the next viral song and get the most streams. For this project, Our group aims to find a way to see if we can develop an algorithm ----that can give artists a competitive edge. 
-Based on the date it was released, bpm, key, energy, danceability, acoustic-ness and more, we are looking to see if we can predict the following:
 
• How many streams?

• Is it in spotify’s playslists?

• Is it in spotify’s charts?

We plan on utilizing some dataset we found on Kaggle that has all those metrics already. We plan to pick a song, remove it from the dataset and then use that dataset to train a model to predict the streams and --other info. This way we have ground truth to compare our results to.

-The dataset can be found in the following link:

https://www.kaggle.com/datasets/zeesolver/spotfy

-Tableau (Public) Link:

https://public.tableau.com/views/SpotifyDataVisualizations/Story1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

### **Methods**

We are trying to predict Streams and if the song made it to spotify’s charts and where it charted.
First we decided to remove all of the variables that were not a float or integer.
Converted the streams from object to int64.

First, we tried to use **Linear Regression** to find if there's 
relation between streams/charts (dependant variable) to all 
the other variables (independent variables).

Then we used the model, **Random Forest**  that is the “opposite” to linear regression and is robust 
against non-linear data to see if there is any improvement.

### **Results**

Overall - Both of them are not great but random forest is slightly better, this is backed up 
by how accurate the mode “thinks” it is using the score method on the test data.
Streams: 97% Random Forest, 65% Linear Regression
Charts: 90% Random Forest, 6% Linear Regression
While Random Forest is closer to the actual value in magnitude, it tends to
cluster its predicted number and does not deviate much

### **Visualization**

We used Tableau and Seaborn

# Total Streams per Year and Top Artists 

<img width="632" alt="Total Streams:Yr and Top Artists" src="https://github.com/jithu-ann/Project-4/assets/153320218/f9b47f72-ebac-47ce-be94-8161c6b757e5">

# Spotify Streams

<img width="2343" alt="Spotify Streams" src="https://github.com/jithu-ann/Project-4/assets/153320218/24bab86c-f926-41d6-a023-5072999e5e15">

# Spotify Playlists

<img width="2337" alt="Spotify Playlists" src="https://github.com/jithu-ann/Project-4/assets/153320218/d5d694c3-2ab7-4458-b57c-6f3722238d28">

# Spotify Charts

<img width="2335" alt="Release Month for Spotify Charts" src="https://github.com/jithu-ann/Project-4/assets/153320218/d110fb30-b122-46f8-85cb-bd36588ee900">



/

### **Conclusions and Recomendations**

• Include Artist Name for modeling & predictions to be likely more accurate

• Further understanding on Spotify % of

    Danceability %
   
    Valence %
     
    Energy %
   
    Acousticness %
   
    Instrumentalness %
   
    Liveness %
   
    Speechiness %
   
• Track YoY changes in statistics for developing further modeling & identifying YoY trendsJ

• Knowing the length of the song will add the to model’s robustness


### **Project contributers (alphabetical order):**

• Bianca Santalla

• Jithu Ann Jacob

• Rob Yaggi

• Steve Deonarine
 
 










