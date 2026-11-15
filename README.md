# weapon-detection-yolov10
Real-Time Weapon Detection Using YOLOv10, Faster R-CNN and OpenCV
# Weapon Object Detection Using YOLOv10 and OpenCV

## 📌 Project Overview
This project focuses on developing an AI-based Weapon Object Detection System using Deep Learning and Computer Vision. It detects weapons such as guns, knives, pistols, rifles, grenades, and handguns from images, recorded videos, and live webcam streams.
The project implements and compares YOLOv10 and Faster R-CNN models, with OpenCV integration for real-time weapon detection and visualization.

## 🎯 Objectives

- Detect multiple weapon categories from images and videos.
- Implement YOLOv10 and Faster R-CNN object detection models.
- Compare model performance using evaluation metrics.
- Identify weapons using bounding boxes, class labels, and confidence scores.
- Enable real-time weapon detection using OpenCV.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| YOLOv10 | Real-time object detection |
| Faster R-CNN | Object detection and comparison |
| PyTorch | Deep learning framework |
| Ultralytics | YOLOv10 training and deployment |
| torchvision | Faster R-CNN implementation |
| OpenCV | Image and video processing |
| Roboflow | Dataset collection and annotation |
| Kaggle | Model training using GPU |
| Jupyter Notebook | Development and experimentation |

## 📊 Dataset Description

- **Dataset Source:** Roboflow
- **Total Images:** 4,145
- **Weapon Categories:** 6
- **Training Set:** 70%
- **Validation Set:** 20%
- **Testing Set:** 10%

### Weapon Categories

1. Gun
2. Knife
3. Pistol
4. Rifle
5. Grenade
6. Handgun

## ⚙️ Methodology

1. **Dataset Collection:** Collected weapon images from Roboflow.
2. **Data Annotation:** Annotated weapons using bounding boxes.
3. **Data Preprocessing:** Applied resizing, normalization, and augmentation techniques.
4. **YOLOv10 Training:** Trained YOLOv10 using transfer learning.
5. **Faster R-CNN Training:** Implemented Faster R-CNN with ResNet-50 and FPN.
6. **Model Evaluation:** Evaluated both models using Precision, Recall, F1-score, and mAP.
7. **Performance Comparison:** Compared both models based on detection performance and speed.
8. **OpenCV Integration:** Integrated YOLOv10 with OpenCV for image, video, and webcam detection.

## 🧠 Model Training Configuration

### YOLOv10

- Epochs: 100
- Batch Size: 16
- Image Size: 640 × 640
- Learning Rate: 0.001
- Optimizer: Adam
- Pretrained Model: YOLOv10s.pt
- Training Platform: Kaggle GPU (NVIDIA Tesla P100)

### Faster R-CNN

- Architecture: ResNet-50 FPN
- Epochs: 10
- Batch Size: 4
- Optimizer: SGD
- Learning Rate: 0.005
- Momentum: 0.9
- Training Platform: Kaggle GPU

## 📈 Model Performance Comparison

| Evaluation Metric | YOLOv10 | Faster R-CNN |
| Precision | 0.9804 | 0.796 |
| Recall | 0.9477 | 0.840 |
| mAP | 0.9102 | 0.795 |

## ✨ Key Features

- Multiple weapon category detection.
- Image-based weapon detection.
- Video-based weapon detection.
- Real-time webcam detection.
- Bounding box visualization.
- Weapon class identification.
- Confidence score display.

## 🚀 Applications

- Airport security surveillance.
- Railway station monitoring.
- Public safety monitoring.
- School and college security.
- Smart city surveillance.

## 📂 Project Files

- `weapon-detection.ipynb` – Main Jupyter Notebook containing the project implementation.
- `README.md` – Project documentation.

## 🔗 Project Links

**Kaggle Notebook:**  
https://www.kaggle.com/code/sai7kaushik/notebookc8e1e03090/notebook

**GitHub Repository:**  
https://github.com/karthik99942/weapon-detection-yolov10

## 👨‍💻 Project Information

**Project Type:** Academic Team Project  
**Institution:** VIT-AP University  
**Department:** Computer Science and Engineering  
**Status:** Completed

## ⚠️ Disclaimer

This project was developed for academic and educational purposes, focusing on automated weapon detection for surveillance applications.
