# Helmet-Detection-using-YOLOv8
Real-Time Helmet Detection System 🏍️⛑️

A deep learning-based solution designed to enhance road safety by automatically detecting helmet compliance among two-wheeler riders. Leveraging the **YOLOv8** framework, this system is built for high-speed inference in smart city environments.

 🚀 Overview

This system utilizes a trained **YOLOv8m (medium)** model to identify riders wearing helmets versus those who are not. By processing live video streams or static images, it provides a scalable tool for automated traffic monitoring and violation detection.

 ✨ Key Features

* **Real-Time Detection:** Optimized for live CCTV and camera feed processing.
* **High Accuracy:** Trained on a massive merged dataset of **9,000+ images**.
* **Smart City Ready:** Designed for integration with traffic surveillance infrastructures.
* **Automated Monitoring:** Reduces the need for manual oversight by authorities.

 🛠️ Tech Stack

* **Framework:** [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
* **Architecture:** YOLOv8m (Medium)
* **Language:** Python
* **Acceleration:** CUDA / GPU-enabled training
* **Dataset Format:** YOLO Standard

 📊 Methodology

1. **Data Collection:** Merged multiple high-quality datasets to create a robust training set of 9,000+ images.
2. **Preprocessing:** Standardized and formatted data into the YOLO structure.
3. **Training:** Utilized GPU acceleration to optimize key performance metrics:
* **mAP** (Mean Average Precision)
* **Precision** & **Recall**


Deployment: Capable of handling real-time inference on video streams.

📥 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/helmet-detection-yolov8.git

# Navigate to the directory
cd helmet-detection-yolov8

# Install dependencies
pip install ultralytics opencv-python

```

🖥️ Usage

To run the detection on a local video file or camera stream:

```python
from ultralytics import YOLO

# Load the trained model
model = YOLO('path/to/best.pt')

# Run inference on a video
results = model.predict(source='traffic_video.mp4', show=True)

```

---

**Would you like me to add a specific "Performance Results" table or a section for "Future Enhancements" (like license plate recognition)?**
