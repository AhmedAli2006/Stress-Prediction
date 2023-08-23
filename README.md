# Stress-Prediction

This repository contains a Dataset, containing health data of 35 students taken from https://github.com/italha-d/Stress-Predict-Dataset


Every Student Folder has

  1) ACC.csv
  2) BVP.csv
  3) EDA.csv
  4) IBI.csv
  5) HR.csv
  6) TEMP.csv
  7) tags_SN.csv
  8) info.txt
 
The Raw dataset is used to predict the stress level. But the time logs for different processes are used from the processed folder because the time logs in the Raw Data folder are not correct for a few students the tags are 9 and others have 7 tags only which does not give clear information about which process started at what time.

The Preprocessing.ipynp notebook contains the pre-processing codes and gives you training and evaluation data.

The Modelling_Prediction.ipynp notebook contains the training of 3 different models, Decision Tree Classifier, Multi-Layer Perceptron (MLP), and Gradient Boosting Classifier.
