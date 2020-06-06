# Motion-Detector
Python program trying to detect the motion of objects using webcam.

#### Features
 - Human Motion Detection System can be used in surveillance and security systems. 
 - The system that this project came up with will be useful for security in a fixed restriction area.Therefore, the background of the targeted area is assumed to be non-moving and considerations of sudden change in lightings are ignored as well. 
 - The idea here is to compute the difference between two frames apply a threshold to separate the pixels that have changed from the others and display them.

#### Under the hood
 - OpenCV library is used for capturing the video through webcam and reading the frames.
 - Gaussian blur is used to blur the frames to improve detection.
