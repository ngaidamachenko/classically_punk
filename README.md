# Welcome to Classically Punk
***

## Task
The goal of the project is to create a program that can identify 
and sort audiofiles by genre with the help of Convolutional Neural Network.

## Description
Through the extraction of various audio features and the utilization of deep learning techniques, the model learns to recognize patterns in music data and make predictions regarding the genre of a given track. The project involves preprocessing audio data, extracting relevant features, training a CNN model, and evaluating its performance to achieve accurate genre classification results.

The model has slightly over 50 features inluding mean and square root average values, and 5 layers.

The structure of the notebook is as follows:
#### 1. Set a path to audiofiles and check if they are being accessed correctly
#### 2. Create a function to extract features from audiofiles
#### 3. Iterate over files and folders. and extract the features
#### 4. Save the extracted features to a respective CSV file
#### 5. Create, run and evaluate the model

Audiofiles set can be downloaded at: https://storage.googleapis.com/qwasar-public/track-ds/classically_punk_music_genres.tar.gz

## Installation
The program requires Jupyter Notebook functionality with the 
following packages: asyncio, numpy, pandas, glob, sklearn, tensorflow and keras.

## Usage
1. Copy the notebook.
2. You can either use existing database or indicate a path to audiofiles, sorted by genres. 
3. Run the book and evaluate performance

### The Core Team
Project completed by Nikita Gaidamachenko

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>

