# Real time Object Detection using Single Shot Multibox Detector SSD 

This project demonstrates real-time object detection using deep learning techniques. It employs the OpenCV library and the SSD MobileNet pre-trained model to detect objects in video streams. The primary focus is on identifying, localizing, and tracking objects in real-time scenarios such as video surveillance, autonomous vehicles, and more.
# Features 

Real-time object detection from video input.

Pre-trained SSD MobileNet model for fast and efficient object detection.

Logging mechanism that records detected objects with timestamps.
Customizable configurations for video path, model settings, and log file output.
# Technologies Used 

Python: The primary programming language for the implementation.
OpenCV: Used for real-time computer vision tasks such as video capture and processing.
SSD MobileNet: A combination of the Single Shot Multibox Detector (SSD) and MobileNet architectures, enabling real-time object detection.
Convolutional Neural Networks (CNNs): Applied to identify and classify objects within the video stream.
# Methodology

Object Detection: The code processes each frame of the video, applies the SSD MobileNet model, and detects objects within the frame.
Video Processing: The video frames are resized, and the model processes them to identify objects. Bounding boxes and class labels are assigned to each detected object.
Non-Maximum Suppression (NMS): This step filters out redundant bounding boxes, ensuring only the most confident detections are retained.
Logging: Detected objects and their respective timestamps are logged into a file for reference.
# Object Detection Workflow:
Load the pre-trained SSD MobileNet model.
Pass the video stream frame-by-frame through the model.
Detect objects and display bounding boxes on the frame.
Apply Non-Maximum Suppression to eliminate redundant bounding boxes.
Log the detected objects with timestamps for each frame.
