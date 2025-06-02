 # 🔍 YOLOv8 Object Detection: Firearm Detection Project

This project demonstrates how to fine-tune a pretrained [YOLOv8](https://github.com/ultralytics/ultralytics) model for object detection — in this case, detecting firearms in images. The goal is to explore real-world computer vision applications, such as visual threat recognition, by building a complete machine learning pipeline from dataset preparation to model inference.

## 🎯 Objective
Develop an end-to-end object detection solution using YOLOv8, with the following goals:
- Collect and annotate image data in YOLO format
- Fine-tune a pretrained YOLOv8 model on a specific object class
- Evaluate model performance and visualize predictions
- Apply the model for real-time and batch inference tasks

## 🧠 Model Details
- Model: `YOLOv8n` (Nano) — optimized for speed and lightweight performance
- Dataset: Custom firearm dataset from public sources (Roboflow, Open Images)
- Framework: Ultralytics `yolo` package

## 🔧 Tools & Technologies
- Python
- YOLOv8 / Ultralytics
- OpenCV
- Matplotlib
- Jupyter Notebook

## ✅ Features
- Image annotation in YOLO format
- Model fine-tuning on custom dataset
- Inference on both local images and webcam input
- Visual outputs with bounding boxes and class confidence

## 📊 Results
- Object detection with real-time or static images
- Example predictions on test set
- Output images saved with annotations

## ⚙️ Installation
```bash
pip install ultralytics opencv-python matplotlib

To set up a virtual environment:

python -m venv .venv
.venv\Scripts\activate 
pip install -r requirements.txt

Getting Started
Run the notebook from notebooks/yolo_obj_det.ipynb to:

Prepare the data

Train the YOLOv8 model

Evaluate predictions

Export and reuse the trained model

📌 Notes
The dataset and labels are used strictly for educational and project purposes.

This project showcases applied skills in computer vision, machine learning, and reproducible workflows.

👤 Author

Emre Yılmaz
📫 yunus_emre94@outlook.com

📄 License
MIT — feel free to reuse for educational or portfolio purposes.