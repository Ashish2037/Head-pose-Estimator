# Head-pose-Estimator

This is a Python script that uses the Mediapipe library for face mesh detection to estimate the head pose in real-time using a webcam.

Prerequisites
Before running the script, make sure you have the following dependencies installed:

OpenCV (pip install opencv-python)
Mediapipe (pip install mediapipe)
NumPy (pip install numpy)



#Description
The script performs the following steps:

Captures video from the webcam.
Detects faces and facial landmarks using the Mediapipe Face Mesh model.
Estimates 3D head pose based on the detected landmarks.
Displays the real-time video feed with the estimated head pose and nose direction.
#Head Pose Interpretation
If the user looks left, the text "Looking Left" is displayed.
If the user looks right, the text "Looking Right" is displayed.
If the user looks up, the text "Looking Up" is displayed.
If the user looks down, the text "Looking Down" is displayed.
If the user's head is in a neutral position, the text "Forward" is displayed.
#Keyboard Shortcut
Press 'q' to quit the application.
#Credits
Mediapipe for the Face Mesh model.
OpenCV for computer vision functionalities.
#License
This project is licensed under the MIT License - see the LICENSE file for details.
