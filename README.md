# Object-Tracker-Using-Yolo-Neural-Network

In this project, we build a real-time object detection model with a modified YOLO neural network. As generalized from natural pictures to other domains, this algorithm outperforms other techniques. As compared with other algorithms, this algorithm is easy to implement and a much more efficient, and the fastest algorithm to use in real-time. Also, the YOLO algorithm is trained on a complete image in predicting boundaries which predict the fewer false positive in background areas.
## Setup Virtual Environment 

In a working directory of your choice, run <code> pip env python3 -m venv <ENV_NAME> </code>, then source <code><ENV_NAME>/bin/activate </code>. Finally, install packages using:

  <code> >>> pip install -r requirements.txt </code>
  
## Video Conversion Using Init Bash Script 

Create a MOV video recording and move it to the working directory. Run <code>./init.sh <PATH_TO_MOV></code> to create subdirectories, convert the MOV video to MP4, and download the YOLOv3 dependencies for OpenCV.

## Get Yolo Dependencies

* wget https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names -P yolov3
* wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg -P yolov3 
* wget https://pjreddie.com/media/files/yolov3.weights -P yolov3 

## Python Implementation

  
