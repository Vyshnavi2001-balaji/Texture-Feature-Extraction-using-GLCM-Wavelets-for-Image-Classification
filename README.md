# Texture-Feature-Extraction-using-GLCM-Wavelets-for-Image-Classification
Image Classification using GLCM and Wavelet using MATLAB

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

# PROJECT OUTCOME
* GLCM texture features showed improved classification accuracy compared to RGB-only methods.
* Euclidean distance performed best among distance measures (25.99% recognition accuracy).
* The proposed GLCM method achieved 29% recognition accuracy, competitive with methods by Serrre et al. (35%), Holub et al. (37%), and Berg et al. (45%), and outperforming Ridgelets+GRNN (22%) .
* Results validate that combining GLCM, Wavelets, and PCA enhances efficiency and recognition accuracy in image retrieval.

# CONCLUSION
The study concludes that GLCM + Wavelets + PCA is an effective approach for texture-based image classification in large datasets.
* Wavelets provide strong feature representation in both time and frequency domains.
* GLCM effectively captures spatial texture patterns.
* PCA reduces computational complexity while preserving discriminant features.
* However, challenges remain in bridging the semantic gap between high-level human perception (color, shape, texture) and low-level machine features.

# FUTURE WORK
The paper suggests:
* Exploring fusion of multiple features (color, shape, and texture together).
* Developing more robust classifiers to improve recognition rates.
* Addressing the semantic gap in image retrieval systems by combining perceptual and machine-learned features.
* Applying the proposed approach to real-time applications and large-scale multimedia databases.

