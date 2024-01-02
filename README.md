# emotionDetection_withMachineLearning

This project consists of detecting the emotion in the images and also in videos using a Machine Learning algorithm (SVM).
# Dataset

I used 2 datasets: the FEED dataset and the CK dataset, both of them contain folders for the 7 emotions.
For the CK dataset :
0 : Anger
1 : Disgust
2 : Fear
3 : Happiness
4 : Sadness
5 : Surprise
6 : Contempt
7 : Neutral

For the Feed dataset :
0 : Neutral
1 : Anger
2 : Disgust
3 : Fear
4 : Happiness
5 : Sadness
6 : Surprise

# Feature extraction : 
To extract the features, we used the HOG and LBP methods.
#Training the results : 
The training results are saved in the files: 'svm_model-feed.sav' for the FEED data and 'svm_model-ck.sav' for the CK data.
# Test the model :
To test the model run : 
python model_testing.py
