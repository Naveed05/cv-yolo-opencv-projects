🧠 YOLOv8 Computer Vision Model Projects

A complete collection of YOLOv8-based detection, tracking, segmentation, and pose estimation models.

📸 Overview
This folder includes multiple real-time Computer Vision applications built using Python, OpenCV, and Ultralytics YOLOv8.
Every script is optimized for practical use with webcam or video input.
These projects demonstrate strong hands-on skills in AI, Deep Learning, and Computer Vision engineering.

🚀 Included Projects

🔍 1. Object Detection — object_detection.py
Real-time YOLOv8 object detection using webcam.
Features:
Bounding box detection
Class labels
Confidence scores
High FPS performance

🔢 2. Object Counting — object_counting.py
Counts all detected objects in each frame.
Features include:
Live object counting
Real-time visualization
YOLOv8-based detections

🎨 3. Object Segmentation — object_segmentation.py
Pixel-wise segmentation using yolov8n-seg.pt.
Features:
Colored segmentation masks
Box + label overlay
Smooth mask rendering

🔁 4. Object Tracking — object_tracking.py
Tracks objects across frames.
Features:
Frame-by-frame YOLO detections
Tracking placeholder (can upgrade to DeepSORT/ByteTrack)
Real-time tracking visualization
visualization

🧍 5. Pose Estimation — pose_estimation.py
Detect 17 human keypoints using yolov8n-pose.pt.
Features:
Skeleton drawing
Keypoint confidence
Smooth real-time pose detection

🛒 6. Customer Detection — customer_detection.py
Detects people/customers in webcam view.
Features:
People detection
Custom confidence thresholds
Retail/CCTV style detection

📁 Folder Structure
CV yolo model projects/
│
├── object_detection.py
├── object_counting.py
├── object_segmentation.py
├── object_tracking.py
├── pose_estimation.py
├── customer_detection.py
│
├── coco.txt
│
├── yolov8n.pt
├── yolov8n-seg.pt
├── yolov8n-pose.pt
├── yolov11n.pt   (optional / if included)
│
├── zidane.jpg
├── demo_videos/
│   ├── Legextension.demo.video.mp4
│   ├── Legpress.demo.video.mp4
│   ├── Pushups.demo.video.mp4
│   ├── Squats.demo.video.mp4


🧰 Tech Stack
Python 3
OpenCV
Ultralytics YOLOv8
NumPy
Deep Learning Models (.pt files)

🧪 Running Any Project
Install required libraries:
pip install ultralytics
pip install opencv-contrib-python
pip install numpy


Run any file:
python object_detection.py
python object_segmentation.py
python pose_estimation.py

📌 Models Included
Model File	Purpose
yolov8n.pt	Standard object detection
yolov8n-seg.pt	Object segmentation
yolov8n-pose.pt	Human pose estimation
yolov11n.pt	Newer YOLO detection model (optional)
🎯 Purpose

This folder demonstrates the essential foundations of modern Computer Vision:
Object Detection
Object Segmentation
Object Counting
Multi-Object Tracking
Pose Estimation
Human Identification
These projects are applicable in domains like:
Retail Analytics
Automation
Surveillance
Fitness AI
Smart Cameras
Robotics

👨‍💻 Author

Mirza Naveed Baig
Computer Vision & AI Developer
Python • YOLOv8 • OpenCV • Deep Learning

⭐ Support
If you like this work, don’t forget to ⭐ star the repo on GitHub!
