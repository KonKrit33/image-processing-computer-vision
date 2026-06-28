# Image Processing & Computer Vision

This repository contains a curated portfolio of image processing and computer vision notebooks implemented in Python. The project focuses on classical image enhancement, spatial filtering, edge detection, corner detection, geometric analysis, object isolation, and image alignment.

The notebooks demonstrate practical workflows for transforming raw visual data into enhanced, interpretable, and analysis-ready images using Python-based image processing techniques.

## Project Overview

The repository includes seven independent notebooks covering fundamental techniques in digital image processing and computer vision.

Each notebook focuses on a specific visual analysis task, starting from image loading and preprocessing and progressing toward enhancement, feature extraction, geometric interpretation, or object isolation.

## Included Notebooks

### 1. Gray-Level Image Transformation

This notebook studies the effect of a grayscale intensity transformation on image brightness and contrast.

The analysis includes:

* Interpretation of a transformation function
* Mapping of input intensity values to output intensity values
* Effect on perceived image brightness
* Application of the transformation to a grayscale image
* Visual comparison between the original and transformed images

### 2. Low-Light Image Enhancement

This notebook applies image enhancement techniques to improve the visual quality of a low-light natural image.

The analysis includes:

* Brightness enhancement
* Contrast improvement
* Color correction
* Local illumination adjustment
* Visual assessment of the enhanced output

### 3. Pollen Image Brightness Enhancement

This notebook applies intensity transformation techniques to improve the perceived brightness of a grayscale microscopy image.

The analysis includes:

* Brightness correction
* Gamma correction / power-law transformation
* Intensity adjustment
* Preservation of structural details
* Comparison between the original and enhanced image

### 4. Moon Image Sharpening

This notebook applies spatial-domain sharpening techniques to enhance fine structural details in a lunar surface image.

The analysis includes:

* Spatial filtering
* Unsharp masking
* Detail enhancement
* Edge and texture sharpening
* Visual comparison before and after sharpening

### 5. X-Ray Image Enhancement and Restoration

This notebook explores forward and inverse image processing pipelines for X-ray image enhancement and approximate restoration.

The analysis includes:

* Estimation of a forward enhancement pipeline
* Brightness and dynamic-range analysis
* Noise interpretation
* Spatial filtering
* Gray-level transformations
* Approximate inverse restoration from an enhanced image

### 6. Edge, Line, Corner and Window Detection

This notebook applies classical computer vision techniques to analyze a structured architectural image.

The analysis includes:

* Main edge detection
* Roof-angle estimation using line detection
* Harris corner detection
* Non-maximum suppression
* Region-of-interest filtering
* Window localization based on detected corner points

### 7. Billiard Cue Detection and Isolation

This notebook applies geometric image analysis and object isolation techniques to billiard images.

The analysis includes:

* Detection of the billiard cue as a dominant straight object
* Cue-angle estimation with respect to the horizontal axis
* Image rotation for geometric verification
* Binary masking
* Object isolation
* Separation of the cue from connected objects
* Image combination to approximate a target output

## Repository Structure

```text
.
├── notebooks/
│   ├── 01_gray_level_image_transformation.ipynb
│   ├── 02_low_light_image_enhancement.ipynb
│   ├── 03_pollen_image_brightness_enhancement.ipynb
│   ├── 04_moon_image_sharpening.ipynb
│   ├── 05_xray_image_enhancement_restoration.ipynb
│   ├── 06_edge_line_corner_window_detection.ipynb
│   └── 07_billiard_cue_detection_isolation.ipynb
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

## Tools and Technologies

* Python
* Jupyter Notebook
* NumPy
* OpenCV
* Matplotlib
* scikit-image
* Grayscale intensity transformations
* Gamma correction
* Histogram and brightness adjustment
* Spatial filtering
* Sharpening filters
* Unsharp masking
* Edge detection
* Hough line transform
* Harris corner detection
* Binary masking
* Morphological operations
* Image rotation
* Image alignment and combination

## Technical Relevance

This repository demonstrates practical skills in image analysis and computer vision, including low-level image enhancement, spatial-domain filtering, feature detection, geometric transformation, and object isolation.

The workflows are relevant to:

* Computer vision pipelines
* Scientific image analysis
* Biomedical image preprocessing
* Industrial visual inspection
* Image enhancement and restoration
* Feature extraction from visual data
* AI-ready image preprocessing workflows

## Notes

The repository contains Jupyter notebooks, input images, and selected output images. Temporary files, cache folders, system-generated files, and local machine-specific files are intentionally excluded.

All notebooks use relative paths so that the repository can be cloned and executed locally while preserving the folder structure.
