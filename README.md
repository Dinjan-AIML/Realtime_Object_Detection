# Realtime Obejct Recognition

Realtime object recognition using the OpenCV +  MobileNetSSD caffemodel.
Realtime Object Recognition is an innovative project leveraging computer vision and machine learning techniques to detect and classify objects in real-time. Whether you're building a smart surveillance system, developing augmented reality applications, or enhancing robotics capabilities, this project provides a robust foundation for object detection tasks.

## Key Features:

-Utilizes state-of-the-art deep learning models for object detection
-Real-time inference for live video streams or camera feeds
-Supports a wide range of objects and environments
-Easily customizable and extendable for specific use cases
-Integration with popular frameworks like TensorFlow and OpenCV
-Seamless deployment on edge devices or cloud platforms

## Installation
All the dependencies can be installed using `pip`. 
```bash
pip3 install -r requirements.txt
```

## How to run this script?

To run the script using webcam as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source webcam
```


Then to run the script using IP as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source web
```
