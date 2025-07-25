# Underwater-Object-Detection-Using-Deep-Learning-Techniques
Project Overview 📄
An underwater object detection system built using the YOLOv8 deep learning architecture, designed to operate effectively in challenging underwater environments characterized by low visibility, distortion, and noise.
YouTube
+13
Scribd
+13
ACM Digital Library
+13

🔧 Core Features
Enhanced detection accuracy under adverse underwater conditions such as turbidity, poor lighting, or particulate distortion
Scribd

Enables comparison of YOLOv8 performance against other architectures like YOLOv5, YOLO-NAS, and RT-DETR using metrics including precision, recall, F1-score, and mAP50
arXiv
+2
Frontiers
+2
MDPI
+2

📦 Technologies & Tools
Component	Description
Deep Learning Framework	Python, PyTorch (YOLOv8 model)
Computer Vision	OpenCV for preprocessing and analysis
Data Handling	Custom annotation scripts for dataset creation
Hardware	Standard CPU environment (e.g., Intel Core i7, 12th Gen)
Models Compared	YOLOv8, YOLOv5, YOLO-NAS, RT-DETR
MDPI
+9
ResearchGate
+9
IAEME
+9
Frontiers
+12
Scribd
+12
MDPI
+12
Preprints
+4
IAEME
+4
arXiv
+4
Frontiers

🧪 Dataset
Created a bespoke aquarium-style dataset containing annotated images of marine species such as fish, jellyfish, sharks, stingrays, penguins, puffins, and starfish
Scribd

📊 Key Outcomes
Achieved a mean Average Precision (mAP50) of approximately 80%, demonstrating significant improvements over earlier models on the custom dataset
MDPI
+6
Scribd
+6
arXiv
+6

Outperformed baseline architectures like YOLOv5, YOLO-NAS, and RT-DETR in detection task benchmarks
Scribd

🚀 Next Steps / Uses
Basis for marine research tools, underwater monitoring, ecological mapping, or robotics applications

Easily extendable to:

Additional marine animal classes

Deployment on edge devices or mobile platforms

Further benchmarking using public datasets like URPC or Brackish

🛠️ Repository Structure (suggested)
bash
Copy
Edit
/dataset/                 # Annotated underwater images & JSON labels
/src/
    ├── train.py         # Training configuration scripts
    ├── eval.py          # Evaluation and benchmarking code
    └── inference.py     # Model inference scripts (non-real-time)
/models/
    ├── yolov8_weights/  # Trained model weights
    └── comparisons/     # YOLOv5, YOLO-NAS, RT-DETR results
/README.md                # Project overview and setup instructions
/requirements.txt         # Python dependencies (PyTorch, OpenCV, etc.)
✅ Sample README Bullet Points (Resume‑Ready)
Designed and built an underwater object detection system using YOLOv8 that handles challenging imaging conditions such as low light and distortion

Created and annotated a custom dataset featuring seven marine object categories—including fish, jellyfish, sharks, and more

Conducted comparative evaluation of YOLOv8 against YOLOv5, YOLO-NAS, and RT-DETR using metrics like precision, recall, F1-score, and mAP50 (~80%)

Implemented the entire pipeline in Python using PyTorch and OpenCV on standard CPU hardware
