# Feature Extraction and Matching using OpenCV

## Overview
This project demonstrates how to detect and locate an object within an image or video stream using **feature extraction** and **matching** techniques with OpenCV.  
It uses **SIFT** for feature detection and **FLANN** for efficient feature matching. Object localization is done with **Homography** to accurately map the object onto the scene.

## What’s Included
- **Feature Detection**:  
  Detect keypoints and descriptors using SIFT (Scale-Invariant Feature Transform).
  
- **Feature Matching**:  
  Match features between the query image and the target image using FLANN-based matcher, with Lowe’s ratio test to filter good matches.

- **Object Localization**:  
  Estimate Homography to find the object in the scene and outline it.

- **Video Detection** *(Bonus)*:  
  Apply the detection pipeline to a video, drawing a rectangle around the detected object in real-time, optimizing by processing every few frames.

## Installation
Make sure you have Python and the required packages installed:
```bash
pip install opencv-contrib-python numpy matplotlib
```

## How to Run
1. **Image Matching**:  
   Run the script to detect and match features between two images and visualize the results.

2. **Video Object Detection**:  
   Run the video script to detect the object in real-time in a video feed.

Press `q` to exit the video window during runtime.

## Project Submitted by
- Hager Tamer Abd El-Fattah — 120210092  
- Noura Moustafa Mahmoud Maklad — 120210150
