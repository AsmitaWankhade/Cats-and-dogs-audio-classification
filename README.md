# Cats-and-dogs-audio-classification

## Steps:
##### 1. Importing required libraries :
numpy, pandas, librosa, tensorflow, sklearn , seaborn

##### 2. Loading train and test data from google drive

##### 3. Pre-processing using librosa :
MFCCs are the Mel Frequency Cepstral Coefficients. MFCC takes into account human perception for sensitivity at appropriate frequencies by converting the conventional frequency to Mel Scale, and are thus suitable for speech recognition tasks quite well.
In audio pre-processing, Mel frequency is a representation of short term power spectrum of sound. Audio sample is converted to mel-
freuency coefficients using : mel(f)=2595*log(1+f/700)
These extracted features are used for training data using a deep network.

##### 4.Check if any null values are present. There are no null values in given dataset. Label encode the classes
##### 5. Build a neural network model. Compile and start the training.
99% accuracy was obtained on training set.
85.07% accuracy is obtained on test set. Confusion matrix drawn : 0-cats,1-dogs
