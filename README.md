# Industrial-Grade Crack Detection with YOLOv11

This repository contains a production-ready infrastructure inspection system using YOLOv11. It is designed to detect and classify cracks and structural faults in industrial environments.

## Overview

The core of this project is the `Infrastructure_crack_detection_improved.ipynb` notebook, which provides a comprehensive pipeline for:
- Environment setup and dataset installation (Roboflow).
- Advanced data augmentations (weather, shadows, debris, etc.).
- Optimized training configurations.
- Performance evaluation and benchmarking.

## Key Features
- **Industrial-Grade Augmentations**: Simulates real-world conditions like fog, sun flare, and drone camera blur.
- **YOLOv11 Integration**: Uses the latest Ultralytics YOLOv11 for high-fidelity detection.
- **Robust Evaluation**: Includes per-class metrics, confusion matrices, and speed benchmarking.
- **Ready for Deployment**: Provides a clear path from training to inference benchmarking.

## Setup

### Requirements
- Python 3.8+
- PyTorch with CUDA support recommended
- Ultralytics YOLOv11
- Albumentations
- Roboflow

### Installation
```bash
pip install ultralytics albumentations roboflow seaborn scikit-learn pyyaml
```

## Dataset
The project uses the "Civil-Faults-Detection" dataset from Roboflow. It detects 11 classes, including:
- Diagonal/Horizontal/Vertical Cracks (Fine, Medium, Severe)
- Pavement Crack
- Tile Damage

## Usage
Refer to the `Infrastructure_crack_detection_improved.ipynb` notebook for the full training and evaluation workflow.

## Author
Ammar Nasir