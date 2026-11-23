# YOLOv8-Animal-Detection
Custom YOLOv8n model for detecting and tracking cats, dogs, and rabbits.
# YOLOv8 Animal Detection and Tracking

## Project Overview
This project uses YOLOv8n to detect and track three animal classes: cats, dogs, and rabbits.

## Dataset
- Total images collected: 360
- Classes: cat, dog, rabbit
- Annotation tool: Roboflow
- Training platform: Google Colab

## Model
- Architecture: YOLOv8n
- Training method: Transfer learning
- Model weights: `weights/best.pt`

## Results
The trained model was tested on animal images and a short video. Object detection and tracking were performed using YOLOv8 and ByteTrack or BoT-SORT.

## Files
- `weights/best.pt`: Trained model
- `video/animal_tracking.mp4`: Five-second tracking demonstration
- `Animal_Detection_YOLOv8.ipynb`: Training and testing code
- `results/`: Model evaluation images

## Limitations
During testing, the model sometimes confused cats, dogs, and rabbits, particularly when multiple animals appeared together.
