# YOLOv8-object-detection
🚀 Real-Time Object Detection using YOLOv8 and OpenCV

This project implements a real-time object detection system using a webcam feed powered by the Ultralytics YOLOv8 Nano model and OpenCV.

The system detects multiple objects from the COCO dataset in real time and draws bounding boxes around them along with their predicted class labels and confidence scores.

📌 Project Overview

This application captures live video from your webcam and performs real-time object detection using a pre-trained YOLOv8n model.

Detected objects are:

Classified into predefined COCO classes

Assigned confidence scores

Surrounded with bounding boxes

Displayed directly on the live video stream

Additionally, cats are highlighted with a purple bounding box for visual distinction.

🧠 Model Used

YOLOv8 Nano (yolov8n.pt)

Pre-trained on the COCO dataset

Lightweight and optimized for real-time detection

🛠️ Dependencies

Make sure you install the following libraries before running the project:

Python 3.x
Math

You can install the required packages using:

pip install ultralytics opencv-python
▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git

Navigate to the project directory:

cd your-repo-name

Make sure the following files exist in the root directory:

object.py
yolov8n.pt

Run the script:

python object.py
🎥 Output

The webcam will open automatically

Objects detected in real time will be displayed with:

Bounding boxes

Class labels

Confidence percentages

Press q to exit the detection window.
OpenCV

Ultralytics YOLOv8
