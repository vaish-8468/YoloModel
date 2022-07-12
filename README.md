# iot-picamera/YoloModel
Repository for occupancy detection system using pi camera.

# YOLO
YOLO — You Only Look Once — is an extremely fast multi object detection algorithm which uses convolutional neural network (CNN) to detect and identify objects.

# The objective is to build a system that has the following features.

-Read the frames from the Video.
-Draw a desired reference line on the input frame.
-Detect the people using the object detection model.
-Mark the centroid on the detected person.
-Track the movement of that marked centroid.
-Calculate the direction of centroid movement (whether it is moving upwards or downwards).
-Count the number of people coming in or going out of a reference line.
-Based on the counting, increment the up or down counter.

# People Counting and Tracking Project Requirements
We can build the deep learning  project locally since it does not have many dependencies.

Install the libraries:
-pip install numpy
-pip install opencv-python==3.4.2.16

Then we need a python file for Centroidtracker.

Here we will use YOLO v3 as our model for detecting the person in the frame. So we need to download YOLO v3 weights and YOLO v3 configuration files as well as the coco classes that is coco.names file. You can download the same from [here](https://drive.google.com/drive/folders/1AhOM31dy8jfLqQ1CcVcXJgWmorG_TzjU).



Thanx!
