# Air Drawing using Python

## Introduction:

This is a project that uses computer vision techniques and machine learning to create an Air Drawing. The project allows users to draw anything they want in the air just by moving their hands. The project uses the OpenCV library for computer vision and the Mediapipe library for hand landmark detection and tracking.

The project involves detecting and tracking the landmarks of a user's hand and using the motion of their hand to draw on a virtual canvas. The user can choose between a brush or an eraser, and can change the brush or eraser size and color.

This project is a great example of the power of computer vision and machine learning. It combines various techniques such as image processing, object detection, and tracking to create a unique and interactive user experience.

## Algorithm:

* [1] Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
* [2] Prepare the canvas frame and put the respective ink buttons on it.
* [3] Adjust the values of the mediapipe intilization to detect one hand only.
* [4] Detect the landmarks by passing the RGB frame to the mediapipe hand detector
* [5] Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
* [6] Finally draw the points stored in array on the frames and canvas .

## Functionality:

The program allows users to draw on a canvas using their hands. It detects hand landmarks using the MediaPipe library, and maps the position of the hand to a point on the canvas. The program also allows the user to select different colours to draw with, as well as clear the canvas.

## User:
The program is designed for users who want to draw on a canvas using their hands.

## Modules:
The program uses the following modules:
•	cv2: OpenCV is a computer vision library used for image and video processing.
•	numpy: NumPy is a library for numerical computations in Python.
•	mediapipe: MediaPipe is a cross-platform framework for building multimodal machine learning pipelines.
•	collections: The collections module provides alternatives to built-in types with additional functionality.
•	deque: A deque is a double-ended queue.

## Technologies:

Front end: The program uses the OpenCV library for displaying the canvas and capturing frames from the webcam.

Back end: The program uses the MediaPipe library for hand landmark detection and mapping the position of the hand to a point on the canvas.

## System Flow Diagram:

![Picture1-removebg-preview (1)](https://github.com/viv3k19/airDrawing-using-Python/assets/82309435/6ffb5158-a8bf-4db9-8623-84d99a1cca64)

## Conclusion:
In conclusion, the Air Drawing project is a great example of the power of computer vision and machine learning. It allows users to draw on a virtual canvas using their hands, and combines various techniques such as image processing, object detection, and tracking. The project uses the OpenCV library for computer vision and the MediaPipe library for hand landmark detection and tracking. The program is designed for users who want to draw on a canvas using their hands, and provides options to select different colours and erase the canvas. Overall, the project demonstrates the exciting possibilities of combining computer vision and machine learning in creating interactive user experiences.

## Screenshot

![image](https://github.com/viv3k19/airDrawing-using-Python/assets/82309435/c1de022b-94aa-448f-b8bc-9baf8389bf38)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.


