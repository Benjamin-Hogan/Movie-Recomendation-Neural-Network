# Movie-Recommendation-Neural-Network
## Building a neural network that will predict personal scores for movies

This is done by importing data via an excel spreadsheet with the properties of (see file):
1. Title (The title of the movie)
2. Runtime (How long the movie is)
3. Genre
4. Sub-Genre
5. Personal score (a rating of of ten of how I liked the moive)

I then one-hot encoded the data and normalized the data.

After that I split the data into *inputs* and *labels* while having filters for the moives I have yet to see.

Next, the data is again split into training and testing data.

The neural network was then created using TensorFlow. 

I trained the network and then tested the network before giving the model the entire data set. 

The model then predicted the scores for all the moives including the ones that I  had yet to see. 

This predictions are then outputed to a excel file. 
