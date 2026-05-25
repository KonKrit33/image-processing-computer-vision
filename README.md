# Image Processing & Computer Vision

This repository contains MSc coursework exercises in Image Analysis and Processing, focusing on grayscale transformations, image enhancement, sharpening, edge detection, corner detection, line-angle estimation, object isolation, and image alignment.

The project demonstrates practical image-processing workflows using Python and Jupyter notebooks, with input images, intermediate outputs, and final processed results.

## Project Overview

The repository includes seven exercises covering fundamental techniques in digital image processing and computer vision.

### Exercise 1: Grayscale Intensity Transformation

This exercise studies the effect of a transformation function on a grayscale image.

The analysis includes:

- Interpretation of the transformation function
- Effect on image intensity values
- Effect on perceived brightness
- Application of the transformation to a grayscale image
- Visual comparison between input and output images

### Exercise 2: Low-Light Image Enhancement

This exercise focuses on enhancing a dark forest image in terms of perceived light and color.

The analysis includes:

- Brightness enhancement
- Contrast improvement
- Color correction
- Visual assessment of the enhanced result

### Exercise 3: Brightness Enhancement

This exercise focuses on improving the perceived brightness of a pollen image.

The analysis includes:

- Brightness correction
- Intensity adjustment
- Contrast-aware enhancement
- Comparison of the original and enhanced image

### Exercise 4: Image Sharpening

This exercise focuses on sharpening an image of the Moon.

The analysis includes:

- Spatial sharpening
- Unsharp masking
- Enhancement of image details
- Visual comparison before and after sharpening

### Exercise 5: Combined Spatial Enhancement Pipeline

This exercise studies how one image may have been transformed into another using combined spatial enhancement methods.

The analysis includes:

- Reverse engineering of the image enhancement pipeline
- Brightness and dynamic-range analysis
- Noise interpretation
- Use of arithmetic operations, gray-level transformations, and spatial filters
- Approximation of the original image from the enhanced version

### Exercise 6: Edge Detection, Angle Estimation, and Corner Detection

This exercise analyzes an image of a house.

The analysis includes:

- Detection of main image edges
- Estimation of the angle of diagonal roof edges
- Corner detection
- Localization of windows based on detected corners

### Exercise 7: Line Detection, Rotation, and Image Combination

This exercise analyzes billiard images to estimate cue orientation and combine image information.

The analysis includes:

- Detection of the billiard cue as a long straight object
- Estimation of cue angle with respect to the horizontal axis
- Image rotation to verify the estimated angle
- Binary masking and object isolation
- Separation of the cue from connected objects
- Combination of two images to approximate a target result

## Repository Structure

```text
.
├── notebooks/
│   ├── Ex_1.ipynb
│   ├── Ex_2.ipynb
│   ├── Ex_3.ipynb
│   ├── Ex_4.ipynb
│   ├── Ex_5.ipynb
│   ├── Ex_6.ipynb
│   └── Ex_7.ipynb
│
├── images/
│   ├── input/
│   │   ├── step_fun.png
│   │   ├── nature_dark_forest.jpg
│   │   ├── pollen-500x430px-96dpi.jpg
│   │   ├── First-photo-of-the-moon-from-Chandrayaan-2_ISRO.jpg
│   │   ├── image_1.jpg
│   │   ├── image_2.jpg
│   │   ├── image11.jpg
│   │   ├── image31.png
│   │   └── image32.png
│   │
│   └── output/
│       ├── moon_unsharp_masking_sharpened.jpg
│       ├── image32_estimated_from_image31.jpg
│       ├── image33.png
│       ├── image33_cue_mask_estimated.jpg
│       └── image33_isolated_cue_estimated.jpg
│
├── README.md
└── .gitignore
```

## Included Notebooks

- `Ex_1.ipynb`: Grayscale intensity transformation and brightness interpretation.
- `Ex_2.ipynb`: Enhancement of a dark forest image.
- `Ex_3.ipynb`: Brightness enhancement of a pollen image.
- `Ex_4.ipynb`: Sharpening of a Moon image using spatial filtering.
- `Ex_5.ipynb`: Combined spatial enhancement and reverse image-processing pipeline.
- `Ex_6.ipynb`: Edge detection, roof-angle estimation, corner detection, and window localization.
- `Ex_7.ipynb`: Billiard cue angle estimation, image rotation, cue isolation, and image combination.

## Tools and Technologies

- Python
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- scikit-image
- Image intensity transformations
- Histogram and brightness adjustment
- Spatial filtering
- Sharpening filters
- Unsharp masking
- Edge detection
- Corner detection
- Binary masks
- Morphological operations
- Line-angle estimation
- Image rotation
- Image alignment and combination

## Relevance

This repository demonstrates practical skills in image analysis and computer vision, including low-level image enhancement, spatial filtering, feature detection, geometric transformation, and object isolation.

The work is relevant to:

- Computer vision pipelines
- Scientific image analysis
- Biomedical image preprocessing
- Industrial visual inspection
- Image enhancement and restoration
- Feature extraction from visual data
- AI-ready image preprocessing workflows

## Notes

The repository contains Jupyter notebooks, input images, and selected output images. Temporary files, cache folders, system-generated files, and local machine-specific files are intentionally excluded.

If running the notebooks locally, make sure that relative paths are preserved according to the repository structure.
