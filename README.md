<!-- PROJECT BANNER -->
<h1 align="center">🔍 YOLOv3 Object Detection — Image, Video & Live Webcam</h1>

<p align="center">
  <strong>A complete YOLOv3-based real-time object detection system using Python & OpenCV.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" />
  <img src="https://img.shields.io/badge/YOLO-v3-orange.svg" />
  <img src="https://img.shields.io/badge/OpenCV-Object%20Detection-green.svg" />
  <img src="https://img.shields.io/badge/Status-Active-success.svg" />
</p>

---

## 📌 Overview

This repository contains a full **YOLOv3 Object Detection System** capable of detecting objects from:

- 🖼️ **Images**  
- 🎥 **Video files**  
- 📷 **Real-time webcam feed**

The system uses **OpenCV**, **NumPy**, and **YOLOv3 configuration files** to achieve accurate and fast inference on 80+ COCO classes.

---

## 📁 Repository Structure
YOLO_OBJECTDETECTION_3/

│── ObjectDetection.ipynb # Jupyter Notebook for testing & experiments

│── object_detection_using_yolo.py # Main YOLO Python script

│── coco.names # COCO dataset class labels

│── yolov3.cfg # YOLOv3 model configuration file

│── test_video.avi # Sample test video for detection


---

## 🚀 Features

✔ Real-time object detection  
✔ Supports **images**, **videos**, and **webcam**  
✔ Uses **YOLOv3 + OpenCV DNN module**  
✔ Draws bounding boxes, labels & confidence  
✔ Works with COCO's 80 object categories  
✔ Fast & optimized frame processing  

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **YOLOv3**
- **NumPy**
- **Jupyter Notebook**

---

## 📦 Installation

### 1️⃣ Clone the Repository

git clone https://github.com/hap4114/YOLO_OBJECTDETECTION_3.git

cd YOLO_OBJECTDETECTION_3

### 2️⃣ Install Dependencies

pip install opencv-python numpy


*(Optional)* Install Jupyter if you want to run the notebook:

pip install notebook


---

## ▶️ How to Run the Project

### **Image Detection**

python object_detection_using_yolo.py --mode image --path your_image.jpg

### **Video Detection**

python object_detection_using_yolo.py --mode video --path test_video.avi


### **Live Webcam Detection**

python object_detection_using_yolo.py --mode webcam



---

## 📸 Output

The system outputs:

- Bounding boxes  
- Object class names  
- Confidence percentages  
- Real-time predictions for webcam mode  

You will see detection windows pop up automatically.

---

## 🎯 Use Cases

- CCTV and surveillance  
- Traffic monitoring  
- Retail analytics  
- Automation & robotics  
- Industrial inspections  
- Smart security systems  

---

## 🧠 Résumé-Optimized Project Description (Copy for Resume)

**YOLOv3 Object Detection System**  
- Developed a real-time object detection pipeline using **Python, OpenCV, and YOLOv3**, supporting image uploads, video processing, and live webcam detection.  
- Implemented COCO dataset class mapping, model preprocessing, bounding-box generation, and confidence-based filtering.  
- Designed modular scripts and a Jupyter Notebook for experimentation, evaluation, and testing.  
- Achieved high-speed inference and smooth real-time performance using OpenCV’s DNN module.  

---

## 👩‍💻 Author

**Himani Anil Patil**  
GitHub: https://github.com/hap4114  

---

## ⭐ Support

If you found this project helpful, please consider giving it a **star ⭐ on GitHub**!


