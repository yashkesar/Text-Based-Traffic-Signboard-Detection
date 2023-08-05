# Text-Based Traffic Signboard Detection

## Project Overview
This project involves the creation of a custom-trained YOLO v8 model designed specifically for the detection and interpretation of text-based traffic signboards. The goal is to improve the accuracy and efficiency of traffic sign recognition in real-world situations, contributing to the development of advanced driving assistance systems and autonomous vehicles.

## Dataset
We created a custom dataset of 400 real-world images, and supplemented this with an additional 100 images generated using DALLE 2.0. This unique combination of datasets has provided a rich foundation for model training and validation. 

Link to the dataset: [Text-Based Traffic Signboard Custom Dataset](https://app.roboflow.com/srm-hybx5/text-based-traffic-signboard-custom-dataset/deploy/4)

## Model
The primary component of our project is the YOLO v8 model, which is used for object localization. This deep learning model was trained on our custom dataset, and is capable of accurately detecting traffic signboards in various lighting conditions, angles, and distances. Additionally, Google's Tesseract OCR engine is employed to interpret the text on detected signboards.

## Application
To bring our model to real-world usage, we have developed an iOS application using Xcode. This app implements our trained YOLO v8 model to detect and interpret traffic signboards. This offers a practical demonstration of the capabilities of our model, and presents a proof of concept for its potential applications.

## Installation
*Note*: Instructions for installation of the iOS app or running the model should be put here.


