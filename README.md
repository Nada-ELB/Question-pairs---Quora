# Question-pairs-Siamese MaLSTM

A simple approach to the "Quora Question Pairs" of Kaggle competition for detecting duplicate questions in QA platforms, based on the work of the article : https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8967103

The goal of this work is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts.

Both training and test sets are provided by Kaggle.

The Model used is Siamese Neural Network with Manhattan distance LSTM

As results this model achieves 83%45 validation accuracy, with a log-loss value of 0.40184 when submitting to Kaggle.

Note: This approach was developed using Google Colaboratory with GPU accelerator, synced with Google Drive for file integration.


Resources :
1st Place Solution
Some Online Interesting Solutions
How to predict Quora Question Pairs Using Siamese Manhattan LSTM
