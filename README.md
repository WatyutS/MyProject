# YOLOv5 Trained Model – Cellphone Detection

This repository contains a YOLOv5 model trained to detect cellphones.

## 📦 File
- `cellphone001.pt` – Trained YOLOv5 PyTorch model

## 🧪 Inference Example (Colab)
```python
!git clone https://github.com/ultralytics/yolov5
%cd yolov5
!pip install -r requirements.txt

# Download weights
!wget https://github.com/WatyutS/MyProject/raw/main/cellphone001.pt

# Run detection
!python detect.py --weights cellphone001.pt --img 640 --source 0
