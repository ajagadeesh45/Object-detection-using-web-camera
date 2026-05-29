# Object Detection Using Webcam

## Overview

This project demonstrates real-time object detection using a webcam with Python and OpenCV. The webcam captures live video and a pre-trained object detection model detects objects frame by frame. Detected objects are displayed with bounding boxes and labels.

This workshop introduces the basics of computer vision and real-time object detection using a webcam.

---

## Objective

- Capture video using webcam
- Detect objects in real time
- Draw bounding boxes around detected objects
- Display object labels with confidence score
- Understand the basics of computer vision

---

## Technologies Used

- Python
- OpenCV
- NumPy
- YOLO / Pre-trained object detection model

---

## Requirements

Install required libraries:

pip install opencv-python  
pip install numpy  

If using YOLO:

pip install ultralytics

---

## Project Structure

Object-Detection-Webcam/

│── object_detection.py  
│── coco.names  
│── yolov3.cfg  
│── yolov3.weights  
│── README.md  

---

## How It Works

1. Open webcam using OpenCV
2. Capture video frame continuously
3. Pass frame to object detection model
4. Detect objects in the frame
5. Draw bounding box around detected object
6. Display object label and confidence score
7. Show output in real-time webcam window

---

## How to Run

### Step 1

Clone the repository

git clone <repository-link>

### Step 2

Move into project folder

cd Object-Detection-Webcam

### Step 3

Run the program

python object_detection.py

---

## Output

The webcam opens and detects objects in real time.

Example detected objects:

- Person
- Bottle
- Mobile Phone
- Chair
- Laptop
- Cup
- Keyboard

Each object is shown with:
- Bounding Box
- Label Name
- Confidence Score

---

## Applications

- Security Surveillance
- Face Detection
- Smart Attendance System
- Autonomous Vehicles
- Traffic Monitoring
- Robotics
- Smart Home Automation
- Retail Object Tracking

---


---

## Conclusion

Object Detection Using Webcam is a beginner-friendly computer vision project that performs real-time object detection using Python and OpenCV. It helps understand how AI can detect and recognize objects from live video input and can be extended into advanced applications like robotics, surveillance, and automation.



Workshop Project – Object Detection Using Webcam

Developed using Python and OpenCV for learning real-time object detection.
