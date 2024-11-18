# SC4001 Neural Network and Deep Learning
 AY24/25 S1 Individual and Team Assignments from NTU CCDS module SC4001 Neural Network and Deep Learning




## Assignment 1: Individual Neural Network Coding Assignment
Question bank can be found [here](https://github.com/Leozk2000/SC4001-Neural-Network-and-Deep-Learning/blob/main/Assignment%201/Assignment_AY2425_sem1.pdf). \
Implement neural network solutions in python for Classification and Regression problems with real life datasets.





## Assignment 2: (A) Deep Learning for ECG Heartbeat Classification
Details of assignment 2 question can be found [here](https://github.com/Leozk2000/SC4001-Neural-Network-and-Deep-Learning/blob/main/Assignment%202/SC4001%20NN%20Assignment%202%20questions.pdf). \
Python Notebook can be found [here](https://github.com/Leozk2000/SC4001-Neural-Network-and-Deep-Learning/blob/main/Assignment%202/NN_Assignment_2.ipynb). \
Assignment Report can be found [here](https://github.com/Leozk2000/SC4001-Neural-Network-and-Deep-Learning/blob/main/Assignment%202/SC4001_Group_Project_Report.pdf).


### Assignment Details
Develop various deep learning models to accurate classify heartbeats from ECG signals into **5 classes**:
* N (0): Normal Beat: This is a regular heartbeat, indicating normal heart function.
* S (1): Supraventricular Ectopic Beat: This type of beat originates from the heart's atria or the AV node, leading to premature contractions.
* V (2): Ventricular Ectopic Beat: These beats originate from the ventricles, often associated with heart conditions like ventricular tachycardia.
* F (3): Fusion Beat: This occurs when a normal beat and an ectopic beat merge, creating a unique waveform.
* Q (4): Unknown Beat: This category is for heartbeats that cannot be definitively classified into any of the other categories. 

Deep learning models used:
* RNN (**98.84%** test accuracy)
* CNN (**98.71%** test accuracy)
* GRU with Attention (**98.93%** test accuracy) 

We also experimented with various data augmentation techniques to better generalise model learning. We could improve our best model (GRU with Attention) up to **98.96%** test accuracy. 

Through the use of Explanability Techniques such as Local Interpretable Model-agnostic Explanations (LIME) and feature map visualisation, insights into how the various models make their classifications are found. 

Datasets used:
- ECG Heartbeat Categorization Dataset: \
https://www.kaggle.com/datasets/shayanfazeli/heartbeat 
- ECG Arrhythmia Classification Dataset: \
https://www.kaggle.com/datasets/sadmansakib7/ecg-arrhythmia-classification-dataset 

 
