# Dogs-Cats-Recognizer
Deep Learning Model trained on the Microsoft Asirre dataset acquired from a Kaggle competition.

# Data Preparation
Original Dataset size: 25,000 images which include 12,500 cats and 12,500 dogs

# Image Preparation
Images must be formatted into pre-processed floating point tensors before being fed into the network

Use the ImageDataGenerator class that belongs to the tf.keras.preprocessing.image API to perform the following tasks:
1) Read files from disk
2) Decode the contents of the images and convert them into a proper grid format as per their RGB content
3) Convert them to floating point tensors
4) Rescale the tensors from values between 0 and 255 to values between 0 and 1 since Artificial Neural Networks work better with small input values

# Model Training
Convolutional Neural Networks have been used to train an Image Classification model. Expect training time to take hours depending on local GPU.
Cloud resources are recommended despite the costs.
Training time has taken approximately 4-5 hours on a local Nvidia Geforce RTX 3060 GPU.
Training run has resulted into over 95% accuracy on validation sets.

# Technologies used
Language: Python
IDE: Jupyter Notebook
Deep Learning Framework: TensorFlow - CNN Algorithm
Dataset: Microsoft Asirre
Dataset Source: Kaggle
