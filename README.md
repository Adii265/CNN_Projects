# CNN_Projects

1. ****YOLO Object Detection using OpenCV****
   
This project implements real-time object detection using the YOLO (You Only Look Once) algorithm. YOLO is a state-of-the-art, deep learning-based technique known for its speed and accuracy in detecting objects in images and video streams. Unlike traditional object detection methods that apply sliding windows across the image, YOLO frames the task as a single regression problem, directly predicting class probabilities and bounding boxes.

**Key Features:**

1. Real-time object detection
2. Uses YOLOv3 model weights for detecting multiple object classes
3. Applies Non-Max Suppression to handle overlapping bounding boxes
4. Visualizes bounding boxes around detected objects using OpenCV and Matplotlib
   
The project utilizes OpenCV's DNN module to load pre-trained YOLO weights and config files. Bounding boxes are drawn around detected objects, showing the confidence level and class of each detected item.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. ****Fashion MNIST Classification****
   
This project focuses on classifying images from the Fashion MNIST dataset, which contains 70,000 grayscale images of 10 different fashion categories (e.g., T-shirts, bags, and shoes). The dataset is widely used for benchmarking machine learning models in image classification.

**Objective:**

Train the model to classify fashion items and achieve high accuracy on the test set.

**How it Works:**

1. The images are fed into a CNN, which automatically extracts features.
2. The model learns to differentiate between various clothing categories based on these features.
3. Finally, it predicts the category of unseen test images.

**Model Architecture**

The model is built using Keras' Sequential API and consists of:

1. Flatten Layer: Converts the 28x28 image into a 1D array.
2. Dense Layer: 128 units with ReLU activation for non-linear transformation.
3. Dense Output Layer: 10 units with softmax activation to predict the probability distribution over the 10 fashion categories.

The model is trained using categorical cross-entropy loss and optimized using the Adam optimizer. The performance is evaluated based on accuracy on the test set.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
