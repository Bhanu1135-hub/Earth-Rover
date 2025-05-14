# Academic Project - Earth Rover

This repo is an implementation of the robot EarthRover. The code of this robot is organised in various folders inside the directory 'earthrover'. The names of these folders briefly indicate the purpose of the code inside them. This repo focusses on the advanced capabilities embedded into the robot via use of Pre-trained Machine Learning models provided by "tensorflow.org" or created via online tool of Google called Teachable Machine. The following projects in this repo demonstrate how we can integrate Tensorflow Lite and such Machine Learning Models on a Raspberry Pi computer. You can further read about them by accessing their individual README.md file.

- Gesture Controls
- Image Classification
- Object Detection
- Object Tracking
- Human Following



## Object Tracking
The code for this project is placed in a directory named 'object_tracking' inside the 'earthrover' directory
The ML model used in this project is placed inside 'all_models' directory.  

Robot is made to track a ball and follow it. You can see the robot's camera view on a browser while it is tracking the ball.

## Human Following
The code for this project is placed in a directory named 'human_following' inside the 'earthrover' directory
The ML model used in this project is placed inside 'all_models' directory.  

Robot is made to follow a human. It is a good human follower :)

## Image Classification

The code for this project is placed in a directory named 'image_classification' inside the 'earthrover' directory. 
The ML model used in this project is placed inside 'all_models' directory.

The robot's camera view is streamed over LAN with overlays of image classification output. Also, if an object is recognised, the robot speaks out its name.

## Gesture Control

The code for this project is placed in a folder named 'tm' inside the 'earthrover' directory. 
The model used in this project is trained through Teachable Machine online tool by Google. 
The model files are present in the same directory. Presently the model is trained to recognise hand gestures. You can train your own model using Teachable Machine and replace the model files to customise the project.
