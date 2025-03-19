# Object Tracking and Counting using YOLOv8 and Supervision

## Overview
This project tracks and counts objects crossing a defined line in a video using YOLOv8 and the Supervision library. It employs ByteTrack for tracking and annotates video frames with bounding boxes, labels, and tracking traces.

## Features
- Detects objects using YOLOv8
- Tracks objects using ByteTrack
- Annotates objects with bounding boxes and labels
- Counts objects crossing a predefined line
- Processes video input and outputs an annotated video

## Installation
Run the following command to install the required dependencies:

```bash
pip install ultralytics supervision==0.18.0
```

## Dataset
The project uses a sample video dataset. Ensure you have a valid video file to process.

## Usage
1. Set up the source video path.
2. Load the YOLOv8 model.
3. Define the counting line.
4. Process the video.

## Output
The processed video with annotated objects and counting results is saved as `count-objects-crossing-the-line-result.mp4`.

## Acknowledgments
- [YOLOv8 by Ultralytics](https://github.com/ultralytics/ultralytics)
- [Supervision Library](https://github.com/roboflow/supervision)

