# Stable Blue Face Filter 

A real-time computer vision project using OpenCV that detects faces from webcam input and applies a stabilized blue visual effect.

## Features
- Real-time face detection using Haar Cascades
- Stable tracking of faces across frames
- Blue color filter + Gaussian blur effect
- Works with live webcam feed

## How It Works
The model detects faces using OpenCV's Haar Cascade classifier.  
To avoid flickering detection, the last known face positions are reused when detection temporarily fails.  
A custom filter is then applied to each detected face region.

##  Run
python main.py


# Controls

Press ESC to exit

# File Structure

haarcascade_frontalface_default.xml
main.py

# Requirements

Python 3.x
OpenCV
NumPy
