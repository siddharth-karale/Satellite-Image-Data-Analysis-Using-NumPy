# WIFIRE Satellite Image Analysis with Numpy

This project analyzes a sample satellite image dataset from the WIFIRE Project using the NumPy library. WIFIRE is an integrated system for wildfire analysis, and this script explores analyzing the aspects of the image related to potential wildfires.

## Data Source

The data source is a satellite image from the WIFIRE Project. The RGB color mapping in the photo is as follows:

* Red pixel indicates Altitude
* Blue pixel indicates Aspect
* Green pixel indicates Slope

Higher values denote higher altitude, aspect, and slope.

## Libraries Used

* numpy
* scipy (not directly used in this example)
* matplotlib.pyplot
* skimage

## Script Overview

The script performs the following analysis on the satellite image:

1. Loads the image as a NumPy array.
2. Investigates the shape and data type of the array.
3. Displays the image and explores pixel values.
4. Modifies specific pixels and explores color manipulation techniques.
5. Performs masking operations to focus on specific regions of the image based on pixel values.
6. Analyzes specific color layers (Red, Green, Blue) corresponding to altitude, aspect, and slope.
7. Creates composite masks to target specific areas based on a combination of color layer thresholds.

## Running the Script

1. Save the script as a Python file (e.g., `SATELLITE IMAGE DATA ANALYSIS USING NUMPY.ipynb`).
2. Install the required libraries (`numpy`, `matplotlib`, `skimage`) using `pip install numpy matplotlib scikit-image`.
3. Run the script from the command line: `SATELLITE IMAGE DATA ANALYSIS USING NUMPY.ipynb`.

This script provides a basic example of image analysis using NumPy on a WIFIRE satellite image. Further exploration can involve more sophisticated feature extraction and wildfire risk prediction techniques.
