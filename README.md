# cnn-knn-classy-muse
Robert Turnage, Prachi Varma, and Grant Wilson

## Objective
We want to build a hybrid K-Nearest Neighbors and Convolutional Neural Network model that will classify different musical genres by audio analysis. Defining the many community described music genres we will attempt to classify by analyzing audio features of frequency and time alongside metrics of track “energy”, tempo, and speed.

## Approach/ Methodology
Features such as frequency patterns, for example salsa drum beat, country steel guitar reveals a potential genre given those specific categories of cultural influences in music. For our experiments specifically we want to focus on attributes which are important in audio files and music specifically. We are particularly interested in frequency, wavelength, amplitude, and pitch to see if we can identify differentiating factors in different genres. The overall process is described below in our block diagram.

First, we will get audio files and features from the GTZAN dataset and from spotify. Next, we will ingest the data and attempt to extract meaningful features for our models. The data will then be split into training and validation sets. Finally, We will run our models, evaluate the results and fine tune the parameters in the hopes of improving accuracy scores. This process will take a few rounds of iteration.

## Datasets
GTZAN genre classification dataset, can be constructed from personal audio library with possible need for similar sizes and frequencies. Spotify Web API data can pull audio features from Spotify tracks. We also were able to pull snippets of Spotify tracks from Everynoise.com in order to have access to a wider array of genres and tracks.

GTZAN genre classification dataset
http://marsyas.info/downloads/datasets.html

Spotify Web API
https://developer.spotify.com/documentation/web-api/
