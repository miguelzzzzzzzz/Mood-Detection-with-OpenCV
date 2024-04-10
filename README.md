# Mood Detection with OpenCV
This project aims to detect emotions in real-time using OpenCV and DeepFace. By analyzing facial expressions, it identifies the dominant emotion displayed by individuals captured in a video stream. The following steps outline the process:

###Face Detection: The OpenCV face cascade classifier is employed to locate faces within the video frames.
###ROI Extraction: For each detected face, a region of interest (ROI) is extracted from the frame.
###Emotion Analysis: DeepFace is utilized to analyze the ROI and predict the dominant emotion (e.g., happy, sad, angry).
###Visualization: The program draws rectangles around detected faces and labels them with the predicted emotions.
###Real-Time Display: The processed frames are displayed in real-time, allowing users to observe emotion changes dynamically.

##Dependencies:
Python
OpenCV
DeepFace
