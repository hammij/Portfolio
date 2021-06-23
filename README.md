# Portfolio
Repository for Data Science and Machine Learning projects I have worked on or am currently pursuing

# [Project 1: Hand Gesture Recognition](https://github.com/hammij/DataMining)
The overall goal of this project is to construct a model which when provided with muscle activity from the forearm will correctly classify the hand gesture that this muscle activity would create. The practical applications of this project stem into the field of artificial limbs, as the ability to classify hand gesture from forearm activity is critical in the development of functional prosthetics.

We were able to do a good classification of the hand gestures using muscle activity. Knowing what EMG signals are and knowing what is noise in them helped greatly in the pre-processing stage which was followed by PCA. This laid the foundation for a neural network to fit the data well and to be able to classify the hand gestures with an average accuracy of 99.44% with cross-validation. The AUC curves that followed made our belief stronger that this indeed is a good model for classifying hand gestures using muscle acivity.
