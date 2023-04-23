# YOLOv8 inference using Ultralytics API

This is a source code of a web application for this article: 
https://dev.to/andreygermanov/create-an-object-detector-using-yolov8-neural-network-and-deploy-it-as-a-web-service-on-python-julia-nodejs-and-javascript-39fn

This is a web interface to [YOLOv8 object detection neural network](https://ultralytics.com/yolov8) 
implemented on [Python](https://www.python.org) that uses a model to detect traffic lights on images.

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
