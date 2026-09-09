# YOLOv11x-C2A-Disaster-Detection
Hyperparameter configuration (args.yaml) for YOLOv11x trained on the C2A dataset for trapped human detection.
# YOLOv11x on C2A Dataset for Trapped Human Detection

This repository contains the training configuration and hyperparameter setup for the baseline evaluation of **YOLOv11x** on the **C2A Disaster-Imagery Dataset**. 

This configuration is intended to ensure full scientific reproducibility for our experimental baseline on aerial Search and Rescue (SAR) human detection.

## Files Included
* `args.yaml`: Contains the exact training configuration, including optimizer (AdamW), learning rate schedule, mixed-precision (FP16/AMP) flags, and both geometric and photometric augmentations used during the 60-epoch training process.

## Framework
* **Architecture:** YOLOv11x 
* **Dataset:** C2A (Combination to Application) Synthetic Dataset
* **Task:** Single-class Object Detection (Human)
