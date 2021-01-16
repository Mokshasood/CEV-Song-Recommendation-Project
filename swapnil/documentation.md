# PROJECT
To develop an ML based song recommender using KNN ad Cosine algorithms.

# Understanding the project
A song recommender is basically a system that makes predictions of any song that a user would have high probability to listen. Any recommendar system usually could be made from 3 basic filtering methods:

1) Collaborative based ( based on past history of similiar kind of user)
2) Content based ( based on past history of user)
3) Hybrid of both

Using these methods one could use algorithm like KNN , Cosine to formulate the algorithm for a song recommender. Now talking of the project-
 In this project we made use of two datasets from kaggle:
1) t consisted of the song name , song id and user id.
2) The other consisted of listen count of a paricular song with particular user.
   
We first combined both the datasets on the basis of song id/name.Then we counted the total number of times a particular song was heard. From this we were able to get the total count and could use a threshold value of total count which would state that below the threshold count the recommender wouldn't recommend that song. This way we used collaboratve filtering to neglect the least heard songs. Then we used KNN and Cosine algorithm combined to get the most related song to any particular song.

# Attribute information

data,data2=two datasets taken from kaggle
overall_data=data after merging
data_with_rating=overall data and additional column for total data count
data_with_table=converting data in tabular form

# OVERVIEW

Basically we build a Machine learning algorithm using KNN (K nearest neighbor) and Cosine algorithm to form the song recommendation system. We used collaborative filtering as major part for filtering the songs. 