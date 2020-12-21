# IFT6758_Kaggle Images
The main task for the data challenge is to predict the number of 'likes' for given details about the simulated profiles of users on social media.

Our best submission does not include images processing. However, we added this submission which includes image analysis. The purpose is to exemplify the data processing required and how it was included in the prediction. Due to colab capabilities, data processing was done in a separated colab notebook.

Files for Images submission. This folder contains the following files:

1. submission_27_Reset.csv corresponds to the prediction generated.
2. Team_26_Social_Dilemma_images.ipynb. Python notebook focused on image pre-traitment.
3. Social_Dilema_06_12_2020_submission27_vMG.ipynb. Python notebook to generate file
4. ift6758-a20.zip. all files for prediction
5. df_test_img_canny.csv and df_train_img_canny.csv. Files generated after image treatment.

Procedure to execute python notebook:
---- Procedure to execute image pre-processing-----
1. Upload Team_26_Social_Dilemma_images.ipynb into colab
2. Upload ift6758-a20.zip file in colab.
3. Run colab Social_Dilemma_Image_pre_analysis.ipynb
4. Files df_train_img_canny.csv and df_test_img_canny.csv will be generated

---- Procedure to execute submission file-----
1. Upload df_train_img_canny.csv and df_test_img_canny.csv into colab. 
2. Upload Social_Dilema_06_12_2020_submission27_vMG.ipynb file in colab.
2. Run colab until submission file generated. Notes:
	1.All the parameter tuning cells have been commented.
	2.EDA has commented. It is not required for submission generation.
3. submission_27_Reset.csv will be automatically generated and saved.


In detail, the following steps are part of the colab file:

1. Study data by exploratory data analysis and do Feature engineering.

2. preprocessing the data

3. Test train split data

4. Fit the model and experiment of different models

5. For the best ensembler fit the model and generate submission file


