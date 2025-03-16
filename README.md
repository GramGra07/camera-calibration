# Camera Calibration

A comprehensive Python toolkit for camera calibration using OpenCV. This project provides tools to calibrate your camera, remove lens distortion, and apply the calibration to live video feeds.

## Overview

Camera calibration is the process of estimating the parameters of a camera's lens and image sensor. These parameters can be used to correct for lens distortion, measure the size of an object in world units, or determine the location of the camera in the scene.

This toolkit includes:

1. **Image Capture Tool**: Capture calibration images from your camera
2. **Calibration Tool**: Process the calibration images to compute camera parameters
3. **Live Undistortion**: Apply the calibration to a live video feed