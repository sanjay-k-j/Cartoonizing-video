# Cartoonise-Video Project

## Description

This project aims to cartoonize any video using a combination of image processing and machine learning techniques. Two different approaches are implemented for cartoonization:

### 1. Using OpenCV Image Processing

The `cartoonise.py` file contains code for cartoonizing images using OpenCV's image processing capabilities. The process involves edge detection and bilateral filtering. First, the edges of the image are detected, followed by the application of bilateral filters for smoothening. Finally, the two images are merged by taking the inverse binary mask of the edges.

### 2. Using K-Means Clustering Algorithm

The `Cartoonise_Kmeans.py` file implements cartoonization using the K-Means clustering algorithm from machine learning. In this approach, the image is flattened into an array, and the K-Means algorithm is applied to find centers. These centers are then used to segregate different color regions in the image, providing a cartoon-like effect. This technique is commonly used for color reduction in image processing.

## System Requirements

Ensure the following dependencies are installed:

- Python 3
- OpenCV
- NumPy

## How to Use

1. Keep the PC wherever you want to cartoonize.
2. Run the Python scripts (`cartoonise.py` or `Cartoonise_Kmeans.py`) based on your preference.
3. Enjoy the cartoonized output.

Note: Make sure you have Python 3 installed on your system along with the required libraries (OpenCV, NumPy) before running the scripts.
Happy cartoonizing!
![image](https://github.com/sanjay-k-j/Cartoonizing_images/assets/79088504/8fec6e5d-2b1d-4200-b328-e00df6a7b552)
