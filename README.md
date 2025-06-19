# AI Lane Detection & Traffic Sign Recognition

This project uses CNNs and YOLOv5 to detect traffic signs and lane markings in real-time using the CARLA simulator.

## Features
- Lane Detection (OpenCV & U-Net)
- Traffic Sign Recognition (GTSRB + CNN)
- CARLA Integration with Live Inference
- Python + PyTorch based models

## Project Structure
- `models/` → Trained CNN/YOLO models
- `notebooks/` → Training notebooks
- `scripts/` → Preprocessing and evaluation
- `carla_integration/` → CARLA streaming + real-time inference
- `docs/` → Report, diagrams, images

## Installation
```bash
pip install -r requirements.txt
