# EC-21

The notebook Noisylabels_tuning provides prediction model of competitive and uncompetitive bids using CleanLab. The steps are:

- GridSearch method for optimal hyperparameters search

- XGBoost classifier prediction with assumption that some of the labels are messed (cleanlab package)

C-firms_M-firms includes further analysis of predicted labels.

- M-firms detection - firms that act like monopolists (place only uncompetitve bids in single-bid auctions and have contracts with 2+ procurers)

- C-firms detection - firms that act like collusive groups (participated together in 2+ auctions with uncompetitive bids. 
Each such firm wins at least once with an uncompetitive bid) 

Data has been included with already generated features using methodology in chapter 3.4 Features of the classifier. 
