##Camera Calibration and 3D Image Transformation
Overview
This repository contains the implementation of camera calibration and 3D image transformation to obtain UV image points. The project is designed to calibrate a camera for accurate image capturing and then perform transformations that map 3D world coordinates to 2D image points, resulting in UV coordinates.

Project Structure
/calibration/: Contains scripts and data for camera calibration, including the use of a checkerboard pattern.
/transformation/: Implements the 3D to 2D image transformation to obtain UV points.
/images/: Sample images and datasets used for calibration and transformation.
Features
Camera Calibration: Utilizes a checkerboard pattern to calibrate the camera, ensuring that image captures are geometrically accurate.
3D to 2D Transformation: Transforms 3D coordinates into 2D UV points on the image plane using the camera matrix and distortion coefficients.
