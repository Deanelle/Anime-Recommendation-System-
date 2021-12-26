Anime Recommendation System 

Context: 

Over the past few years fandom for the anime industry has increased in the United States. With the advent of covid and with more people spending more time indoors, there is a need to be able to find and watch entertaining anime. However, there are tons of options and if you are like, those options can be overwhelming and act as a deterent to watching the anime that you love.
Wtih there being thousands of good anime it gets increasingly difficult to choose and thus more easy for choice paralysis to kick in. Therefore, with this project, I am designing a content-based recommendation system that can help anyone view the types of anime that they enjoy or any company recommend to viewers they anime that they will be more inclined to watch.
About the Data The data comes from MyAnimeList and I downloaded the anime.csv file from Kaggle and it contains information on user preference data from 73,516 users on 12.294 anime. Each user was able to add anime to their completed list and give it a rating and this data is a compilation of those ratings.

The content:

Anime.csv
anime_id: myanimelist.net's unique id identifying an anime.
name: full name of anime
genre: comma separated list of genres for this anime.
type: movie, TV,OVa, etc.
episodes: how many episodes in this show. (1 if movie).
rating: average rating out of 10 for this anime.
members: number of commuinity members that are in thsi anime's "group".
Rating.csv
user_id: non-identifiable randomly generated user-id
anime_id: the anime that the user has rated
rating: rating out of 10 this user has assigned (-1 if the user watched it but didn’t assign a rating)

Since I only looked at the content based features, I chose to only focus on the anime.csv dataframe and not the rating.csv since I was not looking at the user interaction features.
