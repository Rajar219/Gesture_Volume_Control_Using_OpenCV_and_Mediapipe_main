Hand Gesture Volume Control Using Python

This project demonstrates how to control the system volume using hand gestures captured through a webcam. It uses computer vision and hand-tracking techniques to detect the distance between fingers and adjust the volume accordingly.

Features

Real-time hand tracking using a webcam

Volume control based on finger distance

Simple and intuitive hand gestures

Works on most systems with a camera

How It Works

The webcam captures live video frames.

MediaPipe detects hand landmarks.

The distance between the thumb tip and index finger tip is calculated.

If the distance is greater than a threshold, the system volume increases.

If the distance is smaller, the system volume decreases.

Technologies Used

Python

OpenCV

MediaPipe

PyAutoGUI

Requirements

Install the required Python libraries:

pip install opencv-python mediapipe pyautogui

Usage

Ensure a webcam is connected.

Run the script:

python volume_control_python.py


Show your hand to the camera.

Increase finger distance to raise the volume.

Decrease finger distance to lower the volume.

Press Esc to exit the program.

File Description

volume_control_python.py – Main script for gesture-based volume control

Limitations

Requires adequate lighting

Depends on system support for volume key events

Accuracy may vary with hand position

Future Enhancements

Visual volume indicator

Additional gestures (mute, pause, play)

Improved gesture recognition accuracy

Author:

RAJA R
Email: leviraja670@hmail.com
Just tell me.

DEV
