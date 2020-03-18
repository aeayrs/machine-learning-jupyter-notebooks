**Introduction**
A recommendation engine is a model that can predict what a user may be interested in.
When we apply this to the context of movies, this becomes a movie-recommendation engine.
We filter items in out database by predicting how the current user might rate them. This
helps us in connecting the users with the right content in our dataset. Why is this relevant?
If you have a massive catalog, then the users may or may not find all the relevant content.
By recommending the right content, you increase consumption. Companies such as Netflix
heavily rely on recommendations to keep the user engaged.

Recommendation engines usually produce a set of recommendations using either
collaborative filtering or content-based filtering. The differenct between the two approaches
is in the way the recommendations are mined. Collaborative filtering builds a model from the 
past behavior of the current user as well as ratings given by other users. We then use this
model to predict what this user might be interested in. Content-based filtering, on the other
hand, uses the characteristics of the item itself in order to recommend more items to the user.
The similarity between items is the main driving force here. In this chapter, we will focus on
collaborative filtering.