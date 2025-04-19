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
