# burglar_presence_alarm_system_cv

Motion detection system using OpenCV that detects movement from camera or video files.

## Setup

1. Create conda environment:
```bash
conda create -n burglar_alarm python=3.9
conda activate burglar_alarm
```

2. Install OpenCV:
```bash
conda install -c conda-forge opencv
```

## Usage

### Run with camera (default):
```bash
python burglar_presence.py
```

### Run with video file:
```bash
python burglar_presence.py test_video.mp4
```

### Controls:
- Press **Esc** to exit

## Features
- Detects motion by comparing frame differences
- Draws bounding boxes around moving objects
- Saves frames with detected motion as JPG files
- Displays "Motion Detected" text when motion is found
- Supports both camera and video file input
