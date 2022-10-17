# EEG-Data-ML


### About the Dataset
This data arises from a large study to examine EEG correlates of genetic predisposition to alcoholism. It contains measurements from 64 electrodes placed on the scalp    sampled at 256 Hz (3.9-msec epoch) for 1 second. ([More details about the dataset](../main/About%20EEG%20Database.pdf))([Dataset source](https://archive.ics.uci.edu/ml/datasets/eeg+database))

### Objective: 
  Using measurements ( from 64 electrodes placed on the scalp sampled at 256 Hz (3.9-msec epoch) for 1 second ) to recognize whether the subject is alcholic or non-alcholic.


### Approach:
* Preprocess the data (Converting chategorical to Numeric,Nomalizing the data,etc..).
* Made a 2D convolusional nural network model.
* Trained the model for 100 epoch with the training data.
* Validate the model using the testing data.

  
### Validation and Training accuracy:
![Accuracy](https://github.com/D3ViL-NK/EEG-Data-ML/blob/main/Accuracy.png)


#### After training for 100 epoches, the model gave 87.5% accuracy with the testing data.
[View code](../main/Result.ipynb)
