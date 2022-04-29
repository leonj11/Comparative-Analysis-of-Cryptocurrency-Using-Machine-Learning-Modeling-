# Comparative-Analysis-of-Cryptocurrency-Using-Machine-Learning-Modeling-

The project contains 3 python files

# Load Data
In order to Load the data run the file: Yahoo Finance Data Retrieval .ipynb which loads the database for the project.

# Market Analysis 


# Neural Network 

Prerequisites to install:

Install Tensorflow libraires. If you are using Anaconda you can intall Tensorflow form the command pront by runnig the following command: 

pip install tensorflow #CPU only
pip install tensorflow-gpu #For GPU support 

## What to know about the NN Model:

This model took into consideration all the historical data for each cryptocurrency collected from January 1st, 2015, and then it was split into an interval of 60 days for testing and training with the main goal of predicting the 61st day. In other words, the model’s output is the next day closing price in USD.
The structure and intended behavior of artificial neural networks is inspired by the functionality of the human brain. In analogy to the structure of a brain, which consists of billions of highly interconnected neurons, artificial neural networks consist of various, highly connected nodes. Every node receives a certain amount of input from other nodes and, dependent on the received input, each note generates output, which is then passed to subsequent nodes. Hence, information is passed through the network of nodes and transformed by every node on its path.
Once you have installed all the libraties required, run the model: 

Crypto Prediction Neural Network Model.ipynb
