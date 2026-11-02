# Real-Time Perspective Transformation with OpenCV

A real-time image processing application developed using Python, OpenCV, and NumPy.

The application captures frames from a webcam and applies four different perspective transformations to a selected image, displaying the results in a 2×2 comparison panel.

## Features

- Real-time webcam capture
- Interactive image capture using mouse clicks
- Four perspective transformations:
  - Top-down view
  - Right-side perspective
  - Left-side perspective
  - Tilted perspective
- Side-by-side visualization of transformed images
- Double-click to reset the captured image
- Press **Q** to exit the application

## Technologies Used

- Python
- OpenCV
- NumPy
- Jupyter Notebook

## How to Run

1. Install the required libraries:

   ```bash
   pip install opencv-python numpy
   ```

2. Open `imageprocessing.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells.
4. Allow access to your webcam.
5. Align the object within the green rectangle and left-click to capture a frame.
6. View the four perspective transformations in the results panel.

## About the Project

This project demonstrates fundamental computer vision techniques, including perspective transformation, image warping, webcam processing, and mouse event handling using OpenCV.

The transformations are generated from a single 2D camera frame and do not represent true 3D reconstruction.

Developed as an educational image processing project.
