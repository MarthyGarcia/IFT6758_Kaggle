# IFT6758_Kaggle Best submission
The main task for the data challenge is to predict the number of 'likes' for given details about the simulated profiles of users on social media.

Files for Best submission. This folder contains the following files:
1. Best_submission.csv corresponds to the prediction generated.
2. Social_Dilemma_Best_Submission.ipynb. Python notebook to generate file
3. train.csv. CSV file containing the training dataset
4. test.csv. CSV file containing the test dataset

Procedure to execute python notebook:
1. Upload training and testing dataset into colab. Dataset should be called "train.csv" and "test.csv", respectively.
2. Run colab until section Submission File. Run cell Submission file. The latter will generated the predictions on the test dataset.
Notes:
	1.All the parameter tuning cells have been commented.
	2.EDA has commented. It is not required for submission generation.
	3.Cells after submission file are use for evaluation purposes.
3. Submission.csv will be automatically generated and saved.


In detail, the following steps are part of the colab file:

1. Study data by exploratory data analysis and do Feature engineering.

2. preprocessing the data

3. Test train split data

4. Fit the model and experiment of different models

5. For the best ensembler fit the model and generate submission file


