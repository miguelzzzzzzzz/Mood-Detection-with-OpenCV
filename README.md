# Mood Detection with OpenCV
This project aims to detect emotions in real-time using OpenCV and DeepFace. By analyzing facial expressions, it identifies the dominant emotion displayed by individuals captured in a video stream. The following steps outline the process:

1. Face Detection: The OpenCV face cascade classifier is employed to locate faces within the video frames.
2. ROI Extraction: For each detected face, a region of interest (ROI) is extracted from the frame.
3. Emotion Analysis: DeepFace is utilized to analyze the ROI and predict the dominant emotion (e.g., happy, sad, angry).
4. Visualization: The program draws rectangles around detected faces and labels them with the predicted emotions.
5. Real-Time Display: The processed frames are displayed in real-time, allowing users to observe emotion changes dynamically.

#Dependencies:
- Python
- OpenCV
- DeepFace

Test:
![image](https://github.com/miguelzzzzzzzz/Mood-Detection-with-OpenCV/assets/120352678/082f4137-fa10-43be-b8de-03bb44566b54)
