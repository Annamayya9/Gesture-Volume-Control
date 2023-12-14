# Gesture-Volume-Control
A hand-tracking model that helps us to manipulate the device's volume with gestures.
## Required libraries

1. numpy
2. time
3. math
4. pycaw
5. mediapipe
6. ctypes
7. comtypes
8. cv2
## Prerequisites

Install PyCharm
Install cv2 library
## Usage

1. Download the two provided Python files to your local machine.

2. Open and run the "HandTrackingModule.py" file in PyCharm. This file creates the module required to track the hand using Google's Mediapipe library.

3. After running the HandTrackingModule, open and run the "GestureControl.py" file in PyCharm. This file imports the hand-tracking module created earlier and uses the Pycaw library as an API, to enable the control of the device's audio using gestures.
