# Breast Cancer Tumour Mask Creation

This repository contains code and documentation for a project focused on creating accurate binary masks of benign and malignant breast cancer tumours in medical images. This project explores and implements several image segmentation techniques, where Convolutional Neural Network (CNN) approach yielded the best results.

## Overview

The goal of this project was to develop a robust method for automatically segmenting breast cancer tumours in medical images, distinguishing between benign and malignant cases. Using the following techniques:

* **Superpixel-based Binary Segmentation:** Explored the use of superpixels to simplify the image and perform binary segmentation.
* **Edge Detection (Canny and HED):** Investigated the application of Canny and Holistically-Nested Edge Detection (HED) algorithms for identifying tumour boundaries.
* **CNN-based Segmentation:** Developed and trained a Convolutional Neural Network for direct tumour mask prediction.
* **Post-processing:** Applied post-processing techniques, including Canny edge detection and contour analysis (keeping the largest contour), to refine the CNN-generated masks.

The experiments demonstrated that the **CNN-based segmentation approach, coupled with post-processing to retain the largest contour**, provided the most accurate tumour masks.

The original research achieved impressive segmentation results on a higher-performance computing system:

* **Benign Tumours:** 97% accuracy
* **Malignant Tumours:** 89% accuracy

**Please note:** This repository presents a re-implementation and exploration of the methodologies used to achieve those results. Due to computational limitations at home, this project utilises a **smaller neural network model**. Therefore, the performance metrics achieved in this notebook are lower than the original work.

## Purpose of this Repository

This repository serves as a demonstration of the methods and techniques employed in the original research. It aims to:

* Illustrates the process of applying different image segmentation techniques to breast cancer tumour images.
* Provide a practical understanding of the challenges and approaches involved in medical image segmentation.

# The code above represents the effort and intellectual property of Ruth Amey. As an ethical principle, please respect this ownership and refrain from using, copying, or distributing this code without explicit permission.
