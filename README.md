# Convolutional_autoencoder_for_anomaly_detection
Convolutional_autoencoder_for_anomaly_detection

In this repository I will use yet another solution to detect anomalies in Leaf Disease Dataset.

**Introduction:** AutoEncoders which is based on unsupervised machine learning that reduces the dimensionality and reconstructs the data with minimal loss. Although Principal Component Analysis technique seems quite similar, but autoencoders seem to handle the non-linearities better and also learns finer generalizations. 

**Dataset:** I am using the Leaf Disease Dataset. This dataset is divided into 2 classes: Healthy and Anomaly
![Dataset preview](https://github.com/nickdata/Convolutional_autoencoder_for_anomaly_detection/blob/main/Dataset_preview.png)

**IDE:** Colab Notebook

**Methods:** Convolution autoencoder

**Hyper-parameters:** Optimizer - Adam, Metrics - Accuracy

**Evaluation:** I use Mean Absolute error here for model evaluation. I have obtained the accuracy of 90%
![Loss Plot](https://github.com/nickdata/Convolutional_autoencoder_for_anomaly_detection/blob/main/Loss_plot.png)
![Anomaly data reconstruction](https://github.com/nickdata/Convolutional_autoencoder_for_anomaly_detection/blob/main/anomaly_reconstruction.png)
![Healthy leaf reconstruction](https://github.com/nickdata/Convolutional_autoencoder_for_anomaly_detection/blob/main/healthy_leaf_reconstruction.png)

