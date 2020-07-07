# Sun-Spot-Prediction.
The Repository is for Time-series Prediction of Sun Spot data .
In the first section we will compare which model type suits better for sun spot data , and we will optimizer the model through a learning rate scheduler also so we can study how the loss is changing with the learning rate .
We come to the conclusion that GRU might be better for the data and then in the second section we will try to tune the hyperparameter of the GRU model .
We will make multiple models with  different window size , batch size , GRU units and Dense layers and neurons . and see how we can get a model that has lower mae.
Here we can avoid to be to concerned about overfitting since the sunspots are seasonal cycle and we won't to using the model on any other generalized data .
Our aim is to understand the data and the hyper parameters suitable for sun-spot prediction .
