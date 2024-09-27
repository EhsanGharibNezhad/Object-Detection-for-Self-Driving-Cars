# Building an Efficient Object Detection System for Self-Driving Cars

## Summary:
Implemented a state-of-the-art object detection system leveraging YOLOv8 to identify and classify objects in real-time for self-driving cars. The model was trained on a comprehensive dataset, achieving high precision in detecting vehicles, pedestrians, and other critical elements. This project enhanced the vehicle's situational awareness and safety capabilities, contributing to the advancement of autonomous driving technologies.



## Dataset
This dataset is dedicated to self-driving car research and development. 
link: https://www.kaggle.com/datasets/alincijov/self-driving-cars

### Credits
Full credit goes to **Udacity** for creating the images and for the dataset labeling.

### Labels
The dataset contains the following **classic_id** labels:
- **car**
- **truck**
- **pedestrian**
- **bicyclist**
- **light**

### Project Goals

The primary goal of this project is to implement a robust object detection system using the YOLO (You Only Look Once) architecture, enabling real-time identification and classification of objects relevant to self-driving applications. By leveraging deep learning techniques, this system aims to enhance safety and efficiency in autonomous vehicle navigation.

### Modeling: Object Detection with YOLO
YOLO (You Only Look Once) is a real-time object detection system that has gained popularity due to its speed and accuracy. It is designed to detect multiple objects in an image using a single forward pass of a neural network. Unlike traditional object detection methods that apply region proposals and then run a classifier on each region, YOLO treats object detection as a single regression problem, predicting bounding boxes and class probabilities directly from full images.

#### Key Features of YOLO:
- Speed: YOLO is significantly faster than other object detection systems. It processes images in real time, achieving high frame rates with minimal computational cost.
End-to-End Training: YOLO is trained end-to-end directly on the images, meaning the entire pipeline (from feature extraction to classification) is optimized as a single network.
- Unified Detection: YOLO divides the image into a grid and predicts bounding boxes, confidence scores, and class probabilities all at once, leading to a simpler and more unified approach to detection.
- Trade-off between Accuracy and Speed: While YOLO is extremely fast, early versions sometimes struggled with small object detection and had issues with localization. However, later versions, such as YOLOv3 and YOLOv5, have significantly improved both precision and recall, while maintaining high processing speeds.
- Applications: YOLO has been widely used in various fields, including autonomous driving, security surveillance, medical imaging, and even robotics, due to its real-time performance.

![image](https://github.com/user-attachments/assets/bfc07821-8654-4eb0-8144-437fc59d07f2)


![image](https://github.com/user-attachments/assets/0c800b6e-4b68-4831-bbc7-e283ce8128ec)
