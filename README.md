
# Speed Detection Using OpenCV

## Overview

This project uses OpenCV to detect the speed of moving objects in videos or camera streams. It calculates the speed by tracking an object from frame to frame and measuring the change in its position over time.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/speed-detection-opencv.git
## Install the required Python libraries and dependencies:
pip install -r requirements.txt

## Download the YOLOv3 weights for object detection:
wget https://pjreddie.com/media/files/yolov3.weights -O yolo-coco/yolov3.weights

## Download the YOLOv3 configuration file:
wget https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg -O yolo-coco/yolov3.cfg


## Usage

To detect the speed of objects in a video or camera stream, run the following command:

```bash
python speed_detection.py --input <input_video> --output <output_video>
```
## How It Works

The speed detection algorithm works by performing the following steps:

1. **Object Detection**: It uses YOLO (You Only Look Once) for object detection to locate and classify moving objects in each frame.

2. **Object Tracking**: The system tracks the detected objects from frame to frame, linking their positions.

3. **Speed Calculation**: By measuring the distance traveled by the object over a set time interval, the system calculates the speed in pixels per frame.

4. **Annotation**: The speed information is then annotated onto the video frames.

## License

This project is open-source and available under the MIT License. You are free to use and modify this code for your specific needs.

For any questions or support, please contact [your email address].

Enjoy using the Speed Detection Using OpenCV project!

