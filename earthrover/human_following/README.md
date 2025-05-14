# Human Following AI-Robot


## Model files
The ML model used in this project is placed in 'all_models' directory inside parent directory.

## Overview of the Project
Robot detects presence of a person in camera frame using a Machine Learning model 'MobileNet SSD v1 (COCO)' and TensorFlow Lite interpreter.

Both the files 'human_follower.py' and 'human_follower2.py' files are identical in logic. One implements FLASK and the other doesn't, as mentioned below.

### 'human_follower.py'
This file performs human following and streams the robot view over LAN using FLASK (Python's micro Web Framework). 

### 'human_follower2.py'
Pure human following logic. The code pertaing to FLASK is removed.

### 'common.py'
This file contains the utility functions which are required for setting up of Tensorflow Lite interpreter.

 
