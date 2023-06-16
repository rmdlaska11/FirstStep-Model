# FirstStep-Model
## Gathering and Preparing Data
The data we have obtained comes from the Kaggle website with the data name Personality Classification Data: 16 Personalities. This data consists of 60,000 rows and 62 columns, where 60 columns contain questions and 1 column contains 16 personality types.
Source : https://www.kaggle.com/datasets/anshulmehtakaggl/60k-responses-of-16-personalities-test-mbt
## Preprocessing Data
We changed the questions in the data to Indonesian from English. We've also converted the personality column to a numeric form. Next, we perform checks to ensure that there is no missing or duplicate data.
## Exploratory Data Analysis
We visualize to see if the data we have is balanced and how much of each type of MBTI is in the data.
## Build Models
In this model, we use DNN (Deep Neural Network) because the data is categorical. We use three layers with sixteen outputs based on personality classes in the dataset. Next, the model will be compiled using the adam optimizer and the loss will be categorical crossentropy
## Testing The Model
We try to make our own simulation to test whether the model we have is good.
## Deploying Model
We save the model using h5 format then convert it using Tensorflow Lite.
