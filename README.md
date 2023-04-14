# Spotify Song Hit or Flop Predictor
This Jupyter notebook is designed to predict whether a Spotify song will be a hit or a flop. We will be using The Spotify Hit Predictor Dataset (1960-2019) dataset, which consists of features for tracks from the 2000s retrieved using the Spotify web API. The tracks are labeled '1' or '0' ('Hit' or 'Flop') depending on how well they meet some criteria of the author.

# Installation

Clone this repository using git clone https://github.com/yourusername/spotify-song-predictor.git

# Usage

1.	Navigate to the project directory
2.	Open the Spotify Song Hit or Flop Predictor.ipynb file in Jupyter Notebook
3.	Run the code cells in order

# Dataset
The dataset used for this project is available on Kaggle: https://www.kaggle.com/theoverman/the-spotify-hit-predictor-dataset

# Model
We will be using a logistic regression model + minmax scaling technique to predict whether a song will be a hit or a flop based on its features. We will also be using feature selection to determine which features are the most important in making accurate predictions.

# Results
After training and testing our model on the dataset, we achieved an accuracy of 80%. However, it's important to note that predicting the success of a song is not an exact science and there are many factors that can influence a song's popularity.

# Acknowledgements
•	The Spotify Hit Predictor Dataset (1960-2019) dataset by The Overman
•	Kaggle for hosting the dataset and providing a platform for data science projects.

