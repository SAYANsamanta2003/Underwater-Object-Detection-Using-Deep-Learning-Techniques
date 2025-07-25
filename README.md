# 🐠 Underwater Object Detection Using YOLOv8

This project focuses on underwater object detection using **YOLOv8**, designed for analyzing aquatic environments where visual clarity is often compromised by low visibility, noise, and lighting distortion.

---

## 🚀 Project Overview

- Developed a detection system for underwater scenes using the **YOLOv8** deep learning model.
- Trained on a custom dataset containing 7 object categories: **fish, jellyfish, shark, stingray, penguin, puffin, starfish**.
- Compared performance against models like **YOLOv5**, **YOLO-NAS**, and **RT-DETR**.
- Evaluated on metrics such as **precision**, **recall**, **F1-score**, and **mAP50**.

---

## 🛠️ Technologies Used

- **Language**: Python  
- **Frameworks**: PyTorch, OpenCV  
- **Models**: YOLOv8, YOLOv5, YOLO-NAS, RT-DETR  
- **Annotation Tool**: LabelImg / Roboflow  
- **Hardware**: Intel Core i7 (12th Gen), CPU

---

## 📁 Folder Structure

```
.
├── dataset/                  # Annotated images in YOLO format
├── models/                   # Pretrained and trained weights
├── src/
│   ├── train.py              # Model training
│   ├── evaluate.py           # Model evaluation
│   └── inference.py          # Run detection on test images
├── sample_images/            # Sample test images
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/underwater-object-detection-yolov8.git
cd underwater-object-detection-yolov8
pip install -r requirements.txt
```

---

## 🔧 Training

```bash
python src/train.py --data dataset/data.yaml --epochs 100 --model yolov8n.yaml
```

---

## 🧪 Evaluation

```bash
python src/evaluate.py --weights models/yolov8.pt --data dataset/data.yaml
```

---

## 🔍 Inference

```bash
python src/inference.py --weights models/yolov8.pt --source sample_images/test1.jpg
```

---

## 📊 Results

| Model     | mAP50 | F1-Score | FPS (CPU) |
|-----------|-------|----------|------------|
| YOLOv8    | 80%   | 0.78     | ~15 FPS    |
| YOLOv5    | 72%   | 0.70     | ~12 FPS    |
| YOLO-NAS  | 75%   | 0.73     | ~10 FPS    |
| RT-DETR   | 68%   | 0.67     | ~7 FPS     |

---

## 📦 License

This project is licensed for academic use.

---

## ✍️ Author

Created by [Your Name]  
IEEE Publication Link: [10.1109/ISACC65211.2025.10969360](https://doi.org/10.1109/ISACC65211.2025.10969360)
