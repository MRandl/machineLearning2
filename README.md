# machineLearning2
This repository contains the work of our team for the project 2, option B (text classification) of the machine learning class at EPFL. It is divided in multiple notebooks detailing the different methods we used to reach our goals. 

## The best model
The notebook that is interesting for grading as it received our maximal accuracy on the AICrowd dataset is [tfidf_ridge.ipynb](tfidf_ridge.ipynb)

## Citations of other works and libraries
Libraries required for these notebooks to all run are detailed in the notebooks. Most of them are readily available on any Python installation. We also occasionally used small code snippets that were open to use from the Internet, and those cases are cited when used. We used such sources twice : in tfidf-related notebooks for preprocessing, and in BERT for vectorizing the tweets.

## BERT-specific information
Since BERT vectorizing was very slow, it is done in a separate notebook in order to save the vectors in a file, which are then used in notebooks that begin with bert_train_*.
You may run this code on your machine, but we can also provide the vectors file if needed (a little less than 20gb of data). Don't hesitate to contact us for these.

## Data location
Data files should be placed in the data/ folder. Location is clear from the notebook use.
