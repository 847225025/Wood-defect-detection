# Wood-defect-detection

## Project Description
This project utilizes YOLO (You Only Look Once) for detecting 8 different types of defects on wood timber. The model is trained to identify and classify various wood surface defects, providing accurate and efficient defect detection capabilities.

## Environment Setup

### Prerequisites
- Python 3.10
- PyTorch 2.01
- CUDA 11.8

### Installation
1. Install required packages:
```bash
pip install ultralytics
pip install yolo
```

2. Download pre-trained weights:
   - Navigate to `docs/en/models/yolov8` in the YOLO repository
   - Download the pre-trained weights
   - Place the weights file in the root directory of this project

## Verification
To verify that your environment is set up correctly, run the following command:
```bash
yolo predict model=yolov8n.pt source='ultralytics/assets/bus.jpg'
```

If the command executes successfully and produces a prediction output, your environment is properly configured.