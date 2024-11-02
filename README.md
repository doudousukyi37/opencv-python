# opencv-python
关于python语言的opencv图像处理笔记

# OpenCV Image Processing with Python

## Core Concepts
- **Image Representation**
  - 2D array of pixels
  - Color channels (BGR)
  - Data type (uint8, float32)

- **Image Loading and Saving**
  - `cv2.imread()`
  - `cv2.imwrite()`

## Basic Operations
- **Image Conversion**
  - Grayscale: `cv2.cvtColor(src, cv2.COLOR_BGR2GRAY)`
  - Color spaces: BGR, HSV, LAB

- **Image Filtering**
  - Blur: `cv2.GaussianBlur()`
  - Sharpen: `cv2.addWeighted()`
  - Edge detection: `cv2.Canny()`

## Advanced Techniques
- **Feature Detection**
  - Harris Corner Detection: `cv2.cornerHarris()`
  - SIFT: `cv2.SIFT_create()`

- **Object Detection**
  - Haar Cascades: `cv2.CascadeClassifier`
  - HOG + SVM

- **Image Transformation**
  - Rotation: `cv2.getRotationMatrix2D()`
  - Affine: `cv2.warpAffine()`
  - Perspective: `cv2.getPerspectiveTransform()`

## Video Processing
- **Capture Video**
  - `cv2.VideoCapture()`

- **Video Writing**
  - `cv2.VideoWriter()`

## Utilities
- **Drawing**
  - Lines: `cv2.line()`
  - Circles: `cv2.circle()`
  - Text: `cv2.putText()`

- **Color Space Manipulation**
  - Brightness and Contrast: `cv2.convertScaleAbs()`

- **Thresholding**
  - Binary threshold: `cv2.threshold()`
  - Adaptive threshold: `cv2.adaptiveThreshold()`





