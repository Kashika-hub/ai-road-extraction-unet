# AI Enabled Road Extraction using U-Net and PyTorch

## Overview

This project focuses on automated road extraction from high-resolution satellite imagery using Artificial Intelligence and Deep Learning techniques. A U-Net segmentation model implemented in PyTorch was used to classify road and non-road pixels from satellite imagery of Chennai, India.

---

## Problem Statement

Traditional road extraction methods rely on manual digitization, which is time-consuming, labor-intensive, and prone to human error. This project aims to automate road network extraction using deep learning-based image segmentation techniques.

---

## Objectives

* Collect and preprocess high-resolution satellite imagery
* Generate training masks for road and non-road classes
* Train a U-Net segmentation model using PyTorch
* Automatically detect road networks from satellite imagery
* Evaluate model performance using segmentation metrics
* Visualize predicted road extraction outputs

---

## Study Area

The study area is Chennai, Tamil Nadu, India.

### Geographical Coordinates

* Latitude: 12.8° N – 13.2° N
* Longitude: 80.1° E – 80.3° E

### Study Area Characteristics

* Highly urbanized metropolitan region
* Dense road network
* Rapid urban growth and infrastructure development

---

## Dataset Used

* High-resolution satellite imagery
* Digitized road vector data
* Generated road and non-road masks
* Training image patches

---

## Tools & Technologies

* Python
* PyTorch
* U-Net Architecture
* Remote Sensing
* GIS
* Matplotlib

---

# Methodology

1. Satellite image collection
2. Road and non-road digitization
3. Mask generation
4. Training patch creation
5. Dataset preprocessing
6. U-Net model development
7. Model training and validation
8. Accuracy assessment
9. Visualization of predicted outputs

---

# Accuracy Assessment

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 0.9927 |
| Precision | 0.7437 |
| Recall    | 0.8810 |
| F1 Score  | 0.8065 |
| IoU       | 0.6758 |

---

# Key Insights

* The U-Net model achieved very high segmentation accuracy for road extraction.
* Proper dataset preparation and patch generation significantly improved model performance.
* Deep learning techniques can effectively automate road extraction from satellite imagery, reducing manual digitization effort.

---

# Future Improvements

* Integration of advanced segmentation architectures
* Multi-class feature extraction
* Real-time road detection
* Transfer learning for generalized road extraction

---

# Conclusion

A deep learning-based road extraction framework was successfully developed using U-Net segmentation and PyTorch. The model demonstrated strong capability in automatically detecting road networks from high-resolution satellite imagery.

---

## Author

Kashika Venkatesan
B.E. Geoinformatics | Anna University CEG
