# YOLOv8 Pose Detection on the Browser
<p align="center">
  <img src="img/screenshot.jpg" />
</p>

## Description and Rationale
This repository was created to show implementations of YOLOv8 pose detection powered by ONNX and TFJS on the browser environment. It is written in vanilla JavaScript without any frameworks, can be run without any server(on frontend) and demonstrates pose detection on image and web camera. By creating this repository I hope to popularize popular computer vision ML models as YOLO and hope it will find its wide use in STEM related areas. 

The repository contains the following implementations of YOLOv8 on the browser:
* Web camera based YOLOv8 pose detection powered by TFJS. It recognizes single class/object. Works very fast.
* Image based YOLOv8 pose detection powered by TFJS. It recognizes only single class/object. Works very fast.
* Web camera based YOLOv8 pose detection powered by ONNX.It recognizes multiple classes/objects. Works slower.
* Image based YOLOv8 pose detection powered by ONNX. It recognizes multiple classes/objects. Works very fast.

## Setup
Copy the contents of each folder and just run respective html file. All code, i.e. style and scripts are included in html file.  

## Models
-- ONNX
Original YOLOv8n-pose model taken from official Ultralytics repository and converted to onnx. 
```
used model : yolov8n-pose.onnx
size       : ~ 12.7Mb
```

**NMS**

ONNX model to perform NMS operator [CUSTOM].

```
nms-yolov8.onnx
```


## Use another model

It is possible to use bigger models converted to onnx, however this might impact the total loading time.

To use another YOLOv8 model, download it from Ultralytics and convert it to onnx file format.

**Custom YOLOv8 Pose Detection Models**

Please update labels object inside of main.js file.


## Demo
To see demo, please visit
