EE541 Spring 2023 Project 

Title: Computer Vision for ASL Detection and Classificaation
Authors: Aditya Rao; Prithvik Gowda


Train Dataset Size:  69600
Validation Dataset Size:  17400
Test Dataset Size:  28
Unseen Test Dataset Size:  1740


Models Used - ResNet50, DenseNet121

1. EE451-Project.ipynb contains training code. It starts by loading the data and continues to transformation and data augumentation. Its save the fine-tuned model after transfer learning.
Requied Python Packages - torch, torchvision, numpy, matplotlib, sk-learn

2. my_gtts.py - When we run this file, it will load the saved in the same path model from the training file and opens a camera window to detect the hand gestures.
Required Python Packages - Playsound, Image, Torch, Torchvision
