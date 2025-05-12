# Biometric-Project
Fingerprint preprocessing and feature matching using SOCOFing dataset.
This project explores image processing techniques and biometric feature matching on fingerprint data using a subset of the **SOCOFing** dataset. The goal is to apply various computer vision algorithms to enhance, analyze, and match fingerprint images.
The dataset used is [SOCOFing](https://www.kaggle.com/datasets/ruizgara/socofing)
A biometric fingerprint dataset containing 6,000 images. We selected a subset of 100 images for testing and experimentation.

We implemented the following image processing and feature extraction techniques using OpenCV and Python:
- Image Resizing
- Inversion (Negative)
- Translation & Rotation
- Morphological Transformations
- Gaussian and Median Filtering
- Edge Detection:
  - Laplacian Derivatives
  - Sobel Derivatives
  - Canny Edge Detection
- Feature Detection:
  - SIFT (Scale-Invariant Feature Transform)
  - ORB (Oriented FAST and Rotated BRIEF) – used instead of SURF
- Matching: FLANN-Based Matcher
