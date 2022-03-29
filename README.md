# Face-Mask-Detection

Project for COMP 4102 course

# Overview

I have implemented a system where it will detect a user in real time and determine if they are wearing a mask or not. I have utilized the CNN architecture for image recognition, object detection and segmentation but I have tweaked it a little bit to be more accurate than the traditional CNN architecture with the help of MobileNetV2.

# Instructions

1. pip install -r requirements.txt : to install the necessary packages
2. py train_mask.py : to run train_mask.py to generate the model
3. py detect_mask_video.py : to run the program which shows the real time camera and your face with predicted masked or not status
4. you can press 'e' to exit the camera

NOTE: Please ensure that the following variables in the directory are relative to the root directory:

- 'DIRECTORY', 'maskNet' : variable in train_mask.py
- 'faceDetectorPath', 'weightsPath' : variable in detect_mask_video.py
