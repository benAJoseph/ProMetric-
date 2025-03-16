# ProMetric
# Mixture of Expert Models for Multi-Class Brain Disease Classification Using MRI

## Overview
This project leverages artificial intelligence (AI) and deep learning techniques, particularly Convolutional Neural Networks (CNNs), to develop a multi-class classifier for brain disease diagnosis using MRI scans. By employing a Mixture of Experts (MoE) approach, this system enhances diagnostic accuracy and provides a robust AI-assisted tool for medical professionals.

## Features
- **Multi-Class Disease Prediction**: Detects multiple brain conditions, including Alzheimer’s disease, brain tumors, and multiple sclerosis, using MRI images.
- **Deep Learning Model**: Utilizes a fine-tuned ResNet50 architecture for accurate feature extraction and classification.
- **Ensemble and Mixture of Experts (MoE) Approach**: Improves model performance by combining specialized CNN classifiers.
- **Medical Imaging Processing**: Implements pre-processing techniques such as resizing, normalization, and augmentation for optimal model performance.



## Dependencies
Ensure you have the following dependencies installed:
- Python 3.8+
- PyTorch
- NumPy
- OpenCV
- Matplotlib
- Pandas



## Results
The Mixture of Experts (MoE) approach significantly improved classification accuracy, achieving **94.50% accuracy** compared to the traditional ensemble method.

| Model Approach | Accuracy |
|---------------|---------|
| Ensemble (Weighted Avg.) | 57% |
| MoE (Our Approach) | 94.50% |

## Future Scope
- Integration of additional imaging techniques such as **fMRI** and **PET scans** for improved diagnostic capability.
- Expansion of the dataset to cover **rarer neurological disorders**.
- Deployment as a **web-based or mobile application** for real-time clinical use.


## Acknowledgements
We extend our gratitude to our guide **Prof. Binu Rajan MR**, and **Sree Chitra Thirunal College of Engineering** for their valuable support.


## Contact
For any queries, reach out to us at: **onlybusiness.ben@gmail.com**
Code to be added after internal clearance


