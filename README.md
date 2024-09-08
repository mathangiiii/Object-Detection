# YOLO Object Detection

This project utilizes the YOLO (You Only Look Once) object detection algorithm to detect and classify objects within images. The provided Python script uses YOLOv3 with pre-trained weights and configuration to draw bounding boxes around detected objects.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Example](#example)
- [License](#license)

## Installation

1. **Clone the Repository**

   ```
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
2. **Create a Virtual Environment (Optional but recommended)**

```
python -m venv venv
```
Activate the Virtual Environment

Windows:
```
  .\venv\Scripts\Activate
```
macOS/Linux:
```
  source venv/bin/activate
```
3. **Install Required Packages**
Make sure you have opencv-python and numpy installed. You can install them using pip:
```
pip install opencv-python numpy
```


## Usage
To run the object detection script, use the following command:
```
python objdet.py -i path/to/input/image.jpeg -c path/to/yolo.cfg -w path/to/yolo.weights -cl path/to/classes.txt
```
**Parameters**
- i or --image: Path to the input image file (e.g., img1.jpeg).
- c or --config: Path to the YOLO configuration file (e.g., yolov3.cfg).
- w or --weights: Path to the YOLO pre-trained weights file (e.g., yolov3.weights).
- cl or --classes: Path to the file containing class names (e.g., yolov3.txt).
  
**Files**
- objdet.py: Python script for performing object detection using YOLO.
- yolov3.cfg: YOLOv3 configuration file.
- yolov3.weights: YOLOv3 pre-trained weights file.
- yolov3.txt: Text file containing class names for detection.
  
