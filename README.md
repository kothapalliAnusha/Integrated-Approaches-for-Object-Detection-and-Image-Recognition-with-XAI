# Integrated-Approaches-for-Object-Detection-and-Image-Recognition-with-XAI

This project combines cutting-edge object detection, image recognition, and Explainable AI (XAI) techniques to deliver a robust system for defence, surveillance, and security applications. The system not only detects objects and classifies them but also identifies the image source (drone, CCTV, or conventional camera) and provides interpretable outputs for enhanced transparency and trust.

Table of Contents:

->Introduction

->Features

->Datasets

->Technologies Used

->Installation

->Usage

->Results

->Applications





📑Introduction:

In the realm of computer vision, object detection and image recognition play a pivotal role in various applications, especially in defence and surveillance. This project enhances these capabilities by integrating:

✅YOLOv8 for real-time object detection.

✅ResNet50 for accurate image recognition.

✅Explainable AI (XAI) for transparency in model predictions.
Additionally, the system classifies image sources (drone, CCTV, conventional camera) to provide critical contextual intelligence for operational use.

This project has been designed with defence applications in mind, offering real-time performance, accuracy, and explainability in high-stakes environments.

📑Features:

✅Object Detection:

   Real-time object detection using YOLOv8.
   
✅Image Recognition:

   CIFAR-10 dataset classification using ResNet50 for precise object recognition.
   
✅Image Source Classification:

   Distinguishes between images captured by drones, CCTV, and conventional cameras.
   
✅Explainable AI (XAI):

   Implements tools like SHAP and Grad-CAM for transparent decision-making.
   
✅Performance Metrics:

   Evaluate object detection accuracy, source identification precision, and explainability.
   
📑Datasets:

✅CIFAR-10 Dataset:

Contains 60,000 images across 10 classes.
Used for training the ResNet50 model.

✅Custom Dataset:

Contains images captured from drones, CCTV, and ground cameras.
Used for YOLOv8 training and image source classification.


📑Technologies Used:

->Programming Languages: Python

->Deep Learning Framework: PyTorch

->Models:
YOLOv8 for object detection
ResNet50 for image recognition

->Libraries:
OpenCV: Image preprocessing
Matplotlib: Visualizations
Pandas & NumPy: Data handling

->Explainable AI Tools:
SHAP
Grad-CAM


📑Installation:

Follow these steps to set up and run the project:

Clone the Repository:

		git clone https://github.com/yourusername/your-repo-name.git
		cd your-repo-name
  
Create a Virtual Environment:

	python -m venv env
	source env/bin/activate  # On Windows: env\Scripts\activate
 
Install Dependencies:

	pip install -r requirements.txt
 
Prepare Datasets:

Download CIFAR-10 dataset using PyTorch utilities.
Place the custom dataset under the data/ folder.

📑Results:

➡️Object Detection:
Achieved high precision and accuracy using YOLOv8.

➡️Image Recognition:
ResNet50 effectively classified CIFAR-10 images with strong performance metrics.

➡️Image Source Classification
Successfully differentiated between drone, CCTV, and ground camera images.

➡️Explainable AI:
Visualized predictions using SHAP and Grad-CAM, ensuring transparency in decision-making.


📑Applications:

->Defence and Security:

Real-time monitoring and threat detection.
Analysis of surveillance footage with context.


->Surveillance Systems:

Enhanced camera-based monitoring.


->Autonomous Systems:

Context-aware AI for autonomous drones and vehicles.
