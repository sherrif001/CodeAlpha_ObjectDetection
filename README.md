# YOLO Object Detection System

## Overview:
This project implements a **real-time object detection system** using **YOLOv5** for detecting objects in video streams or webcam input. The system uses the **Ultralytics YOLOv5** pre-trained model to identify and classify objects in real-time from a video or webcam feed. The system is built with **Python**, **OpenCV**, and **Tkinter** to provide a graphical interface for easy usage.

## Features:
- **Real-Time Object Detection**: Detect and classify objects in a video stream or webcam feed.
- **Simple GUI**: Use the Tkinter interface to start, stop, and visualize object detection easily.
- **Customizable**: Download YOLOv5 pre-trained models and use them directly in the app.
- **Progress Bar**: Visual feedback for download progress.

## Requirements:
To run this project, you will need the following Python packages:

- **Python 3.7+**
- **YOLOv5** for object detection.
- **OpenCV** for real-time video processing.
- **Tkinter** for GUI creation.

You can install the dependencies using the `requirements.txt` file.

### **Install Dependencies**:
1. Clone the repository:
    ```bash
    git clone https://github.com/sherrif001/CodeAlpha_ObjectDetection.git
    cd CodeAlpha_ObjectDetection
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### **Required Packages**:

To run the project, you will need to install the required dependencies listed in `requirements.txt`:

```txt
opencv-python==4.5.5.64
opencv-python-headless==4.5.5.64
torch==1.10.0
ultralytics==8.0.0
numpy==1.21.0
requests==2.26.0
