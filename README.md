# EN3160 Assignment 1 – Intensity Transformations and Neighborhood Filtering

This repository contains my implementation for EN3160 Assignment 1, covering intensity transformations, histogram equalization, spatial filtering, and image scaling using OpenCV and NumPy.

## Contents
- Intensity transformation with custom breakpoints (piecewise linear LUT)
- White/gray matter accentuation on a brain proton density image
- Gamma correction on the L plane (L\*a\*b\* color space)
- Vibrance enhancement using a Gaussian-based saturation transform
- Custom histogram equalization (full image and foreground-only)
- Sobel filtering (filter2D, custom implementation, and separable kernels)
- Image zooming with nearest-neighbor and bilinear interpolation, verified using normalized SSD
- GrabCut-based foreground/background segmentation with background blur
- Bilateral filtering (OpenCV and custom implementation) compared against Gaussian blur

## Structure
- `EN3160_Assignment1.ipynb` – Main Jupyter notebook with all code and results
- `230045X_a01.pdf` – Final report exported from the notebook

## Author
C.S.B. Anthony (230045X)
