## Object Detection & Counting using YOLOv8 and OpenCV

Live object detection using your webcam with object counts

This project uses the YOLOv8n model from Ultralytics and OpenCV to perform real-time object detection via webcam. It identifies objects, draws bounding boxes, labels them, and displays a live count of total detected objects on the screen.

Demo image :- [Link Text](https://www.linkedin.com/posts/jaayysoni_just-completed-a-real-time-object-and-people-activity-7317939352876060672-bFsP?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFgtzsoBH9VBnC0b0IRgXlvUR205L_JPUz4)

Features
•	Real-time object detection from webcam feed
•	Detects and labels multiple objects using YOLOv8
•	Displays live object count on-screen
•	Uses lightweight YOLOv8n model for fast performance

Tech Stack
•	Python 3.13.2
•	Ultralytics YOLOv8
•	OpenCV

Installation
1. Clone the repo
   ```
    git clone https://github.com/jayysoni/object-detection-yolov8.git
   ```
   ```
    cd object-detection-yolov8
   ```
2. Create a virtual environment (optional but recommended)
   ```
   python -m venv venv
   ```
   ```
   source venv/bin/activate
   ```
 # On Windows: 
 ```
 venv\Scripts\activate
```
3. install required files (pip,pip3)
```
   ultralytics
```
```
   opencv-python
```
   Example :-
   ```
                           pip install ultralytics opencv-python
   ```
   or
   ```
                           pip3 install ultralytics opencv-python
   ```

4.	Run the detection script
   ```
    python hand.py
   ```

How It Works / Workflow Section<br>

1. The script initializes a webcam feed using OpenCV.<br>
2. YOLOv8n (a pre-trained model by Ultralytics) processes each frame in real time.<br.
3. Detected objects are labeled with bounding boxes.<br>
4. The total number of detected objects is displayed on the screen.<br>

Limitations<br>

Detection quality may vary in low lighting.<br>
The script runs on CPU by default; performance can be improved with GPU.<br>
No class-specific count breakdown (just total count),<br>

Future Improvements<br>

Add class-wise object counting (e.g., 2 persons, 1 cup).<br>
Include sound alerts for specific object detection.<br>
Save annotated video or snapshots to disk.<br>
Option to switch to custom-trained YOLOv8 model.<br>

## Contributing
Pull requests and suggestions are welcome.
