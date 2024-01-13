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
Copy the contents of each folder and just run respective html file. All code, i.e. style and scripts are included in each html file.  

## Models
<b>ONNX</b>. Original YOLOv8n-pose model taken from official Ultralytics repository and converted to onnx. NMS file was created using adapted version of Wahyu Sentianto's <a href="https://github.com/Hyuto/fun/tree/master/test-onnx-graph-surgeon">graph surgeon example</a>.  
```
used model : yolov8n-pose.onnx
size       : ~ 12.7Mb
```
**NMS**

ONNX model to perform NMS operator.

```
nms-yolov8n-pose.onnx
```
<b>TFJS</b>. Original YOLOv8n-pose model taken from official Ultralytics repository and converted to TFJS.

## Use another model

It is possible to use bigger models converted to onnx, however this might impact the total loading time.

To use another YOLOv8-pose model, download it from Ultralytics and convert it to ONNX or TFJS format.

**Custom YOLOv8 Pose Detection Models**

The example of custom YOLOv8 pose detection model will be demonstrated soon. 


## Demo
To see demo, please visit
