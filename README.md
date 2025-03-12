# Retinal-OCT-Image-Classification
A deep learning-based system for classifying retinal OCT images into four categories (Normal, CNV, DME, Drusen). Uses ResNet-50 and a custom CNN for automated diagnosis. Achieves 99.34% accuracy with ResNet-50. Future work includes hyperparameter tuning and scalability.


## Overview
This project focuses on automated classification of retinal Optical Coherence Tomography (OCT) images into four categories:  
- **Normal**
- **Choroidal Neovascularization (CNV)**
- **Diabetic Macular Edema (DME)**
- **Drusen**

Using deep learning, we compare a **ResNet-50** transfer learning model with a **custom CNN model**. The dataset consists of **84,495 labeled OCT images**. ResNet-50 achieved a superior test accuracy of **99.34%**, outperforming the custom CNN model.

## Models Used
- **ResNet-50** (Pre-trained on ImageNet, fine-tuned for OCT images)
- **Custom CNN** (Designed for lightweight classification)

## Dataset
The dataset includes OCT scans categorized into four classes and is preprocessed with resizing, normalization, and data augmentation.

## Key Results
- **ResNet-50:** 99.34% accuracy, test loss of 0.033
- **Custom CNN:** 97.21% accuracy, test loss of 0.106
- ResNet-50 performs better in distinguishing overlapping features between CNV and DME.

## Future Work
- Hyperparameter tuning for improved performance.
- Ensemble learning approaches for higher accuracy.
- Deployment as a web-based diagnostic tool.

## Authors
- **Ritika Pandey**, **Sumedha Sanjeev Galgali**, **Garima Gambhir**  
  Master's in Data Analytics, The University of Western Ontario
