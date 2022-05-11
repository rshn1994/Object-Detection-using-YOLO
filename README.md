# YOLO object detection using OpenCV
Object detection using YOLO 

### YOLO V3 

For this project YOLO V3 object descriptor has been used (particularly YOLO trained on the COCO dataset).

The COCO dataset consists of 80 labels, full list of classes that can be detected are obtained 
<a href="https://github.com/pjreddie/darknet/blob/master/data/coco.names" target="_blank"><b>using this link.</b></a>

Pre- trained model files for YOLO V3 dectector has been used from <a href="https://pjreddie.com/darknet/yolo/" target="_blank"> <b>Darknet team.</b> </a>


## Dependencies 

- Python Version: `3.8.8`
- Numpy: `1.19.2`
- OpenCV: `3.4.16.59`

## Object Detection in Images 

### To Run the project

- `python yolo_od.py [-h] [-c CONFIDENCE] [-t THRESHOLD] image_files [image_files ...]`

### Screenshot
<img src="https://github.com/rshn1994/Object-Detection-using-YOLO/blob/main/Obj_Det_Img/images/street_YOLO.jpg">

## Object Detection in Videos

### To Run the project

- `yolo_video.py [-h] [--video VIDEO]`

### Screenshot

<img src="https://github.com/rshn1994/Object-Detection-using-YOLO/blob/main/Obj_Det_Vid/Videos/car-street-yolo-out-py.gif">




