# YOLOv1 Implementation

- This repository contains a simple implementation of the YOLOv1 (You Only Look Once) object detection algorithm, inspired by the original paper:  
- **"You Only Look Once: Unified, Real-Time Object Detection"** (CVPR 2016) by Joseph Redmon et al.



## Files

- `YOLOv1 Implementation.ipynb` — Jupyter Notebook with the YOLOv1 code and explanations.
- `Redmon_You_Only_Look_CVPR_2016_paper.pdf` — Original research paper.



## Features

- Custom implementation of the YOLOv1 architecture.
- Forward pass demonstration and prediction visualization.
- Step-by-step explanation inline in notebook (if available).
- Simple and beginner-friendly code structure.



## Running the Code

1. **Clone this repository**: <br>
   zsh <br> 
  git clone https://github.com/Salvatore-2512/YOLOv1-Implementation.git <br> 
  cd YOLOv1-Implementation

3. Open the notebook:<br>
   jupyter notebook "YOLOv1 Implementation.ipynb"
   
4. Run each cell to execute the implementation.

## YOLOv1 Summary
- Treats object detection as a regression problem.
- Single neural network predicts bounding boxes and class probabilities directly from full images in one evaluation.
- Fast and efficient: real-time object detection on images and video.

## Architecture
- The original YOLOv1 architecture uses 24 convolutional layers followed by 2 fully connected layers.

 ## References
- Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016).
  You Only Look Once: Unified, Real-Time Object Detection (arXiv)
