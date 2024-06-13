# BCI_Final_Project

## Introduction
We aim to explore emotion classification through a brain-computer interface system using the SEED dataset. The SEED dataset categorizes emotions into three types: neutral, positive, and negative. In the data preprocessing phase, we apply a bandpass filter and ASR to filter the data, and use ICA to reduce the number of channels and remove noise. We then process the SEED dataset using eight machine learning models: **Decision Tree, Gaussian, KNN, Random Forest, Linear SVM, Polynomial SVM, RBF SVM**. The performance of these models is evaluated based on three metrics: precision, recall, and accuracy. Ultimately, we identify the model that best distinguishes between the three types of emotions.


## Dataset


## Model Framework


## Validation & Results
Although the accuracy of our eight models is not very high, our study differs from others in that we performed ICA processing and analyzed the data using multiple ML models. This approach allows for a deeper exploration to identify the relatively advantageous model, providing a valuable reference for future research.

## Usage


## References
1. Wei-Long Zheng, and Bao-Liang Lu, Investigating Critical Frequency Bands and Channels for EEG-based Emotion Recognition with Deep Neural Networks, accepted by IEEE Transactions on Autonomous Mental Development (IEEE TAMD) 7(3): 162-175, 2015. [link] [BibTex]

2. Ruo-Nan Duan, Jia-Yi Zhu and Bao-Liang Lu, Differential Entropy Feature for EEG-based Emotion Classification, Proc. of the 6th International IEEE EMBS Conference on Neural Engineering (NER). 2013: 81-84.

3. https://github.com/rasoulghaznavi/MLSEED
