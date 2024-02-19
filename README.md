Face Detection with OpenCV
This project demonstrates real-time face detection using OpenCV.

Installation
1) Make sure you have Python installed (https://www.python.org/downloads/).
2) Install the OpenCV library: pip install opencv-python

Running the Code
1) Open a terminal or command prompt in the project directory.
2) Run the Python script: python face_detection.py

Usage
The webcam will start capturing video.
Faces in the video will be detected and highlighted with green rectangles.
Press "x" to stop the video capture.

Features
Sets the video resolution to 1920x1080 (can be adjusted in the change_resolution() function).
Uses Haar cascade classifier for face detection.
Displays detected faces with green rectangles.

Additional Notes
This code utilizes OpenCV 3.x or newer.
It's compatible with most webcams.
Adjust the scaleFactor in facedetect.detectMultiScale() to fine-tune face detection sensitivity.

