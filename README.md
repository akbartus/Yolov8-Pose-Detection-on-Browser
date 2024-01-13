# YOLOv8 Pose Detection on the Browser
<p align="center">
  <img src="img/screenshot.jpg" />
</p>


This repository presents example implementations of YOLOv8 pose detection powered by ONNX and TFJS. It is written in vanilla JavaScript without any frameworks and demonstrates pose detection on image and web camera.

## Setup
To see it at work, just run index.html file. 

## Models

YOLOv8n model converted to onnx with input dimensions of 416x416. 

```
used model : yolov8n.onnx
size       : ~ 12.5Mb
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
