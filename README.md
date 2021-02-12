# EC-21

The notebook Noisylabels_tuning (Jupyter Notebook) provides prediction model of competitive and uncompetitive bids using CleanLab.
If you run this file you get:

- GridSearch method for optimal hyperparameters search

- XGBoost classifier prediction with assumption that some of the labels are messed (cleanlab package)

- Shares of each class: predicted and actual, competitve and uncompetitive (Chapter 4 Results)

C-firms_M-firms (R Markdown) includes further analysis of predicted labels.

- M-firms detection - firms that act like monopolists (place only uncompetitve bids in single-bid auctions and have contracts with 2+ procurers)

There you can find Fig. 2, Fig. 3 and Fig. 4

-  Proportion of uncompetitive bids versus the number of firms per procurer by region (Fig. 1)

- C-firms detection - firms that act like collusive groups (participated together in 2+ auctions with uncompetitive bids. 
Each such firm wins at least once with an uncompetitive bid) 

There you can find Fig. 5

Data has been included with already generated features using methodology in chapter 3.4 Features of the classifier. 
