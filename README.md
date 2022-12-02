# SLAM: Simultaneous Localisation and Mapping

This project is a Python implementation of a NN-SLAM algorithm that takes a video as input and estimates the camera position and the depth map at each frame. The SLAM algorithm uses PyTorch.

## Requirements

This project requires Python 3.6 or higher and PyTorch 1.0 or higher. You also need to install the following Python packages:
- numpy
- matplotlib (optional, for plotting)
- opencv-python (optional, for video reading and writing)

## Usage

To run the SLAM algorithm on a video file, use the following command:
```bash
python slam.py --video <video_file> [--output <output_file>]
```

