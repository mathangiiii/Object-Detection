# YOLO Object Detection
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) 
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
- This project utilizes the YOLO (You Only Look Once) object detection algorithm to detect and classify objects within images. The provided Python script uses YOLOv3 with pre-trained weights and configuration to draw bounding boxes around detected objects.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Proof of Concept](#proof-of-concept)
- [Contributors](#contributors)

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
  
## Files
- objdet.py: Python script for performing object detection using YOLO.
- yolov3.cfg: YOLOv3 configuration file.
- yolov3.weights: YOLOv3 pre-trained weights file.
- yolov3.txt: Text file containing class names for detection.

Download YOLOv3 Weights

Download the YOLOv3 weights file using the following command:
```
Invoke-WebRequest -Uri "https://pjreddie.com/media/files/yolov3.weights" -OutFile "yolov3.weights"
```

## Proof of Concept

[Video of Live Input Footage](https://drive.google.com/file/d/1NYw3qUR5ls4kRQBDCiF9f4NdSBRBNVVt/view?usp=sharing)

## Contributors
- **Mathangi N**: [mathanginarayanan2004@gmail.com](mailto:mathanginarayanan2004@gmail.com)
  
