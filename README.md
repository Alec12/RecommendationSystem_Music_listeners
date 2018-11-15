# RecommendationSystem_Music_listeners
Using Collaborative Filtering, Linear, and Blended Models to form a recommendation system for music listeners


Taken from three csv files (Songs, Users, and Ratings) I develop a predictive model that predicts how each user will rate different songs within the database. This model incorporates an incomplete database of music ratings, and uses the library SoftImpute to make predictions to account for the unavailable data. We then develop a collaborative filtering model with (6) archetype weights per individual. This then helps us make better predictions; by forming archetypes, we can weigh individuals' actions on the likelihood of others with similar rating preferences. From there, we blend this model with a linear model. 
