# CKD-CHRONIC KIDNEY DISEASE PREDICTION USING DEEP-LEARNING
We used two deep learning models, called Convolution Neural Network(CNN) and Long Short Term Memory(LSTM) to predict the Chronic Kidney Disease and we used pre-processing methods are Label Encoder, Handling Missing Values and Normalization.
After applying CNN and LSTM models on dataset, we noticed that CNN performed more accurately on both datasets.
The proposed models cnn and lstm achieved accuracies of 98.75% and 96.25% for 80- 20 training-testing partition.
High accuracy was attained by CNN so, it can be concluded that CNN is used to predict Chronic Kidney Disease.

To implement this project we have designed following modules
1.Upload Chronic Kidney Dataset: using this module we will upload dataset to application and then plot number of NON-CKD and CKD patients graph
2.Preprocess Dataset: using this module we will read dataset and then replace missing values with 0 and then normalize dataset values and then split dataset into train and test where application will be using 80% dataset for training and 20% for testing
3.Run CNN Algorithm: using this module we will input 80% training data to CNN algorithm to train a model and this model will be applied on 20% test data to calculate prediction accuracy
4.Run LSTM Algorithm: using this module we will input 80% training data to LSTM algorithm to train a model and this model will be applied on 20% test data to calculate prediction accuracy
5.Comparison Graph: using this module we will plot accuracy graph between algorithms
6.Predict Disease from Test Data: using this module we will upload test data and then ensemble model will predict weather test data is Normal or contains CKD disease

