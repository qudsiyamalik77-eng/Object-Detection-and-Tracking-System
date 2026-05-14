# 🎯 Real-Time Object Detection and Tracking System

## 🚀 Overview
This project is a professional-grade video analysis tool that leverages Deep Learning to identify objects and track their movement across video frames. Unlike simple detection, this system "remembers" objects by assigning them unique persistent IDs, making it ideal for traffic monitoring, security, and crowd analysis.

## ✨ Key Features
- **Intelligent Detection:** Powered by the YOLOv8 (You Only Look Once) architecture for state-of-the-art accuracy.
- **Robust Tracking:** Implements the SORT (Simple Online and Realtime Tracking) algorithm, utilizing Kalman Filters and the Hungarian Algorithm for ID persistence.
- **Interactive Web UI:** Features a modern, responsive dashboard built with Gradio for seamless video uploads and instant processing.
- **Export Ready:** Automatically processes videos and provides a high-quality download link for the tracked output.

## 🛠️ Technical Stack
- **AI/ML:** YOLOv8, SORT Algorithm
- **Libraries:** OpenCV, FilterPy, Ultralytics, NumPy
- **Interface:** Gradio (Python-based Web UI)
- **Engine:** Python 3.x

## ⚙️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/Object-Detection-and-Tracking-System.git](https://github.com/YourUsername/Object-Detection-and-Tracking-System.git)
   pip install -r requirements.txt
