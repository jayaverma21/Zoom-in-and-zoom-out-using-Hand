# Zoom-in-and-zoom-out-using-Hand

This project demonstrates how to use hand gestures to zoom in and out of a webcam feed using OpenCV and the HandTrackingModule from cvzone.

# Features
Real-time hand detection using a webcam.
Detects the distance between the thumb and index finger to control the zoom level.
Smooth zooming in and out based on hand gestures.

# Requirements 
Python 3.x
OpenCV
numpy
cvzone

# Installation 
git clone https://github.com/your-username/zoom-in-out-hand-gesture.git
cd zoom-in-out-hand-gesture
pip install opencv-python numpy cvzone

# Code Explanation :- 
The main script zoom_in_out_hand_gesture.py does the following:

Initializes the HandDetector from the cvzone module with a detection confidence of 0.8.
Captures video from the webcam.
Detects hands and landmarks in each frame.
Calculates the distance between the tips of the thumb and index finger.
Maps this distance to a zoom level.
Applies the zoom to the frame and displays it.
Ends the application when the 'q' key is pressed.
