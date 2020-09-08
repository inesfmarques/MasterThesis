# MasterThesis
Telecommunication Recommendation System

There are 3 files in this repository:

model.ipynb addresses the brute-force approach. We implement several Machine Learning algorithms on our dataset and evaluate them by computing the weighted F1-score and the confusion Matrix. Finally, since the results were not so great, we try resampling techinques with one of the ML methods.

multistepmodel.ipynb adresses the multistep approach. We divide the classes into groups by their cumulative relative frequency and for each step we have a different algorithm - we select the more appropriate one from those applied in model.py, using the same evaluation metrics.

classifier.ipynb implements the final chosen model for each approach and evaluates their Top 3 Accuracy. 

The global variable total is common to all the notebooks and it represents the maximum number of classes.
