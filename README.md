# Multiview-Hand-Pose
## Descritions of Project
- We will take an input image, and detect the "keypoints" in the image. Our dataset consists of hands, and the so called keypoints are the joint locations of the hand. We will regress from the image matrices to the keypoint location vectors.
#### Steps
- Download this dataset : https://www.kaggle.com/kmader/multiview-hand-pose
- The dataset will consist of images of the joints and 3-dimensional position coordinate files. You need to project 3D coordinates to 2D coordinates to ease the problem for the network. To do this, you can run the 'generate2Dpoints.py' script inside the folders (utils) where you downloaded the data set. (Note: this script is written in python 2)
- After finding the 2 dimensional coordinates, we need to write the coordinates of the bounding boxes into the txt files. For this, we can use the 'generateBBoxes.py' script.

- NOTE : I used the data in the annotated_frames folders in the preprocessing and modeling parts.
