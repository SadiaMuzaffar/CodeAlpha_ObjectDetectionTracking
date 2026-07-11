# CodeAlpha_ObjectDetectionTracking
# Object Detection & Tracking — CodeAlpha AI Internship 

Real-time object detection and tracking on video using a pretrained 
YOLOv8 model.

## How it works
1. Load a pretrained YOLOv8 model (yolov8n) using Ultralytics
2. Process video frame-by-frame using OpenCV
3. Run detection + tracking together using model.track() — 
   this assigns a persistent ID to each detected object across frames
4. Draw bounding boxes, labels, and tracking IDs on each frame
5. Save the annotated output as a new video file

## Tools used
Python, OpenCV, Ultralytics YOLOv8

## Input
Sample traffic/pedestrian video (public test footage)

## Output
Video with bounding boxes, object labels, and tracking IDs 
overlaid on detected objects (cars, people, etc.)

## How to run
Open `ObjectDetection_Tracking.ipynb` in Google Colab, upload a 
video file, and run all cells. Output video will be saved as 
`output.mp4`.
