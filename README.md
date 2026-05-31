# Aerial-guardian
Aerial Guardian is a drone-based computer vision system
# Drone-Based Person Detection and Tracking

## Overview

This project implements a computer vision pipeline for detecting and tracking multiple persons from aerial drone footage using the VisDrone dataset.

The system combines object detection and multi-object tracking to accurately identify and follow people in challenging drone-captured videos.

## Features

- Person detection 
- Multi-object tracking
- Support for drone footage
- Bounding box visualization
- Track ID assignment
- Performance evaluation on VisDrone dataset

## Dataset

Dataset Used:
VisDrone MOT Task 4 Validation Set


## Project Structure

```
project/
│
├── dataset/
├── models/
├── outputs/
├── videos/
├── detect_track.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Drone-Person-Detection.git
cd Drone-Person-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run detection and tracking:

```bash
python detect_track.py
```

## Results

The system detects and tracks multiple persons across drone video sequences.

### Example Output

- Person Detection
- Unique Track IDs
- Annotated Video Output

## Technologies Used

- Python
- OpenCV
- YOLOv8
- ByteTrack
- NumPy

## Future Improvements

- Real-time deployment
- Improved tracking in crowded scenes
- DeepSORT integration
- Edge-device optimization

## Author

Kanika 

B.Tech Computer Science Engineering-jiit


