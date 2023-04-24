# Traffic Lights Object Detector using YOLOv8 neural network

This is a source code of a web application for this article: 
https://dev.to/andreygermanov/a-practical-introduction-to-object-detection-with-yolov8-neural-network-3n8c

This is a web interface to [YOLOv8 object detection neural network](https://ultralytics.com/yolov8) 
implemented on [Python](https://www.python.org) that uses a model to detect traffic lights and road signs on images.

## Install

* Clone this repository: `git clone git@github.com:AndreyGermanov/yolov8_pytorch_python.git`
* Go to the root of cloned repository
* Install dependencies by running `pip3 install -r requirements.txt`

## Run

Execute:

```
python3 object_detector.py
```

It will start a webserver on http://localhost:8080. Use any web browser to open the web interface.

Using the interface you can upload the image to the object detector and see bounding boxes of all objects detected on it.
