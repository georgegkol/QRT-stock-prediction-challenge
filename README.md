The goal of the project is to predict the direction of stock prices given the price and traded volume of the stock for 20 previous days.
First, 10 new features are calculated by aggregating the available data (price and volume) by sector, industry etc.
15 significant features are identified by fitting the dataset to a random forest classifier. 
These are then passed on to a 3-layer neural network that is trained over 5 epochs and yields a 51.49% accuracy on the test set.
