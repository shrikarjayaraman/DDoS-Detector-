# DDoS-Detector-
A python implementation that compares various ml models for DDoS detection including, SVC, KNN, Gaussian and Random Forest models

Using the Network Attack Logs Dataset found on Kaggle by Jacob Van steyn
Link: https://www.kaggle.com/datasets/jacobvs/ddos-attack-network-logs

The dataset contains around 2,100,000 labelled network logs from various types of network attacks.
The types of network attacks logged are: UDP-Flood, Smurf, SIDDOS, HTTP-FLOOD, & Normal traffic

In this implementation we will use the SVC and Gaussian models separately and run the test on the data 
both of them give a similar result of ~89%

next we will train the above models along with the KNN model and pass them through a Random Forest Classifier
we see that the result is better while using the ensemble than while using it individually
Using Random Forest ~98%



