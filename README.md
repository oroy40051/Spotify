# Spotify
Spotify Genre Prediction
I use machine learning techniques to predict the top genre of a song given various numerical and categorical features.
The approach of one hot encoding the categorical variables and adding the sparse matrix to the dataset during training and evaluation
reulted in a mjor improvement.
A voting classifier with multiple models that had hyperparameter optimization done through GridSearchCV produced an accuracy of between 75-78 % on the validation set.
