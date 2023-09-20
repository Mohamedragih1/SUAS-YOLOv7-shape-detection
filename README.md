# YOLOv7 Object Detection with Roboflow and PyTorch

## Introduction

This report provides a streamlined guide to performing object detection with YOLOv7 using the Roboflow platform and PyTorch. It outlines the essential steps for setting up the environment, training the model, running inference, and visualizing detection results.

## Dataset

1. Dataset link: [Link](https://universe.roboflow.com/musa-almaz-p7onb/suas-shape-detection) 

2. Dataset contains 13 classes: circle, cross, heptagon, hexagon, octagon, pentagon, quartercircle, rectangle, semicircle, square, star, trapezoid, triangle

3. Total annotated images are 2000 (1700 train, 200 validation, 100 testing)

![dattta](https://github.com/Mohamedragih1/SUAS-YOLOv7-shape-detection/assets/93843532/2295c121-7df4-4f8c-beef-9dc228f38ede)


## Setup

4. **Clone Repository**: Clone the YOLOv7 repository and navigate to the project directory.

  ```bash
   !git clone https://github.com/WongKinYiu/yolov7
   %cd yolov7
  ```

5. **Install Dependencies**: Install the necessary Python packages and the Roboflow package.

6. **Roboflow Initialization**: Initialize Roboflow by providing your API key.

7. **Access Roboflow Project**: Access your Roboflow project by specifying your workspace and project names.

8. **Download Dataset**: Download the dataset from Roboflow.

## Training

9. **Navigate to Directory**: Change to the YOLOv7 project directory.

10. **Download Model Weights**: Download the YOLOv7 model weights.

11. **Check GPU Availability**: Verify GPU availability for training.

12. **Start Training**: Initiate YOLOv7 model training with custom parameters.

## Inference

13. **Run Inference**: Navigate to the YOLOv7 directory and perform object detection on test images. Adjust the confidence threshold as needed.

## Results Visualization

14. **Display Detection Results**: Visualize detection results in the notebook.

![image](https://github.com/Mohamedragih1/SUAS-YOLOv7-shape-detection/assets/93843532/56fb9dad-28b1-475e-aede-51856e559bb3)

![image](https://github.com/Mohamedragih1/SUAS-YOLOv7-shape-detection/assets/93843532/6cb3f094-420c-4bbe-9da4-98a5bde1a397)

This report provides an overview of the steps required for YOLOv7 object detection with Roboflow and PyTorch. For detailed instructions and code snippets, refer to the sections above
