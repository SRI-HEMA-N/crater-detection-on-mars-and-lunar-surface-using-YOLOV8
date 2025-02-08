# Crater Detection on Lunar and Mars Surface using YOLOv8

## 📌 Overview
This project focuses on detecting craters on the lunar and Martian surfaces using the YOLOv8 deep learning model. Crater detection is crucial for planetary exploration, hazard avoidance, and understanding planetary evolution. The project leverages advanced computer vision techniques and deep learning to automate and improve crater identification.

## 🚀 Features
- **Automated crater detection** using the YOLOv8 model
- **High accuracy of 89.6%** in detecting craters
- **Real-time prediction and bounding box visualization**
- **Dataset preprocessing and augmentation** for improved model performance
- **Web-based interface** for user-friendly crater detection

## 📊 Dataset
- The dataset is obtained from **Kaggle** and consists of lunar and Martian surface images labeled with crater locations.
- **Data Augmentation** techniques such as rotation, scaling and contrast enhancement were applied to improve model robustness.

## 🛠️ Technologies Used
- **Programming Languages**: Python
- **Deep Learning Framework**: PyTorch, Ultralytics YOLO
- **Computer Vision**: OpenCV
- **Web Framework**: Flask (for deployment)

## 🏗️ Model Architecture
- **YOLOv8 (You Only Look Once)** is used for real-time crater detection.
- The model is fine-tuned on labeled crater datasets.
- Bounding boxes and confidence scores are used for crater localization.

## 📈 Training Process
- Dataset split into **80% training, 10% validation, 10% testing**.
- Optimized using **Adam optimizer** and **cross-entropy loss**.
- **Batch size = 16, Learning rate = 0.001**.

## 🎯 Results and Performance
- **Model Accuracy**: 89.6%
- **Precision**: 88.4%
- **Recall**: 90.1%
- **F1-Score**: 89.2%
- Output images with detected craters are stored in the `results` directory.

## 🌍 Application Scope
- Space missions and planetary surface analysis
- Autonomous navigation for rovers and landers
- Geology and impact crater studies
- Future Mars and lunar exploration planning

## 🤝 Contributing
Contributions are welcome! Feel free to fork, submit issues or open a pull request.

## 📬 Contact
For inquiries or collaborations, contact: **srihemanataraj@gmail.com**

