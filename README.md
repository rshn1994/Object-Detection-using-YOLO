# YOLO object detection using OpenCV
Object detection using YOLO 

### YOLO V3 

For this project YOLO V3 object descriptor has been used (particularly YOLO trained on the COCO dataset).

The COCO dataset consists of 80 labels, full list of classes that can be detected are mentioned in the lik below 
<a href="https://github.com/pjreddie/darknet/blob/master/data/coco.names" target="_blank"><b>using this link.</b></a>

Pre- trained model files for YOLO V3 dectector has been used from the link below 
<a href="https://pjreddie.com/darknet/yolo/" target="_blank"> <b>Darknet team.</b> </a>


## Dependencies 

- `Python Version`: 3.8.8
- `Numpy`: 1.19.2
- `OpenCV`: 3.4.16

## Object Detection in Images 

### To Run the project

- `python yolo_od.py [-h] [-c CONFIDENCE] [-t THRESHOLD] image_files [image_files ...]`

### Screenshots
![Image](/Object%20dection%20using%20image/1.png)

<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/Object%20dection%20using%20image/2.png">


## Object Detection in Videos

### To Run the project

- `yolo_video.py [-h] [--video VIDEO]`

### Screenshot

<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/Object%20detection%20using%20video/car.gif">




