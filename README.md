
# Pencil Sketch with Python

This project demonstrates how to create a pencil sketch effect from an input image using Python and OpenCV.

## Introduction

Pencil sketching is a popular artistic technique that mimics the appearance of a pencil drawing. In this project, we leverage computer vision techniques to convert a color image into a pencil sketch.

## Installation

To run the code in this project, you need to install the `opencv-python` package. You can install it via pip:

```bash
pip install opencv-python
```

## Usage

1. **Input Image**: Provide an input image (e.g., `dog.jpg`) in the project directory.

2. **Running the Script**: Execute the provided Python script `pencil_sketch.py` in your Python environment.

3. **Output**: The script will display the original image followed by the pencil sketch version.

## Approach

1. **Read Image**: Load the input image using OpenCV.

2. **Convert to Grayscale**: Convert the color image to grayscale.

3. **Invert Image**: Invert the grayscale image to obtain a negative image.

4. **Blur Image**: Apply Gaussian blur to the inverted image to smoothen it.

5. **Blend Images**: Blend the grayscale image with the inverted blurred image to create the pencil sketch effect.

6. **Display Results**: Display the original image and the pencil sketch side by side.

## Repository Structure

```
.
├── dog.jpg                   # Sample input image
├── pencil_sketch.py          # Python script for creating a pencil sketch
└── README.md                 # This README file
```

## Dependencies

- opencv-python



