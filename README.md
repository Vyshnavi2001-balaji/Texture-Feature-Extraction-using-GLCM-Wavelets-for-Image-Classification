# Texture-Feature-Extraction-using-GLCM-Wavelets-for-Image-Classification
Image Classification using GLCM and Wavelet using MatLab

# PROJECT OVERVIEW

The project focuses on image classification in large datasets using texture feature extraction techniques. The study uses the Gray Level Co-occurrence Matrix (GLCM), combined with Discrete Wavelet Transform (DWT) and Principal Component Analysis (PCA), to extract meaningful texture features from images. Classification is carried out using different distance measure techniques, particularly highlighting Euclidean distance. The system is validated on the Caltech-101 dataset, a challenging benchmark with 9,165 images across 101 object categories.

# PROJECT DESIGN

The design integrates multiple stages of image retrieval and classification:

# 1. Pre-processing:
Images are resized, converted from RGB to grayscale, and dimensionality is reduced using PCA.

# 2. Feature Extraction:
Texture features are extracted using GLCM (contrast, entropy, homogeneity, energy) along with wavelet features to capture both spatial and frequency information.

# 3. Similarity Matching & Classification:
Feature vectors of query images are compared with database vectors using distance measures (Euclidean, Manhattan, MSE, Angle-based).

# 4. Dataset & Validation:
Implemented on Caltech-101 dataset; retrieval accuracy is evaluated across different projection vectors and distance measures.

<img width="890" height="1304" alt="image" src="https://github.com/user-attachments/assets/6a22553d-4980-4a1b-b12c-54c6e5e12610" />

