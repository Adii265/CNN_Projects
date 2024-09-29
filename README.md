# CNN_Projects

1. ****YOLO Object Detection using OpenCV****
   
This project implements real-time object detection using the YOLO (You Only Look Once) algorithm. YOLO is a state-of-the-art, deep learning-based technique known for its speed and accuracy in detecting objects in images and video streams. Unlike traditional object detection methods that apply sliding windows across the image, YOLO frames the task as a single regression problem, directly predicting class probabilities and bounding boxes.

**Key Features:**

1. Real-time object detection
2. Uses YOLOv3 model weights for detecting multiple object classes
3. Applies Non-Max Suppression to handle overlapping bounding boxes
4. Visualizes bounding boxes around detected objects using OpenCV and Matplotlib
5. 
The project utilizes OpenCV's DNN module to load pre-trained YOLO weights and config files. Bounding boxes are drawn around detected objects, showing the confidence level and class of each detected item.
