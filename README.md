# ToothSegmentation-Xray

## Abstract
The ToothSegmentation-Xray project aims to develop a system for accurately segmenting teeth from panoramic X-ray images and measuring their orientation and dimensions using deep learning techniques.

## Introduction
This project utilizes U-Net architecture for image segmentation, focusing on enhancing dental diagnostics through automated analysis. By processing X-ray images, the system extracts essential measurements that aid in treatment planning.

## Objectives
- To implement a U-Net model for tooth segmentation.
- To measure tooth orientation and length accurately.
- To provide a user-friendly interface for input and output of X-ray images.

## Methodology
1. **Input:** Panoramic X-ray images.
2. **Preprocessing:** Grayscale conversion, noise reduction, and image normalization.
3. **Segmentation:** Application of U-Net for isolating teeth.
4. **Post-processing:** Generation of binary masks and contour detection.
5. **Feature Extraction:** Calculation of orientation and length measurements.

## Expected Results
- Accurate segmentation of teeth from X-ray images.
- Reliable measurements of tooth orientation and dimensions.
- Improved efficiency in dental assessments.

## Progress
- **Achieved:** Implementation of preprocessing and segmentation modules.
- **Next Steps:** Validate the model against a larger dataset and refine measurement accuracy.

## Challenges
- Variability in image quality.
- Ensuring the robustness of the segmentation process.

## Future Work
- Explore integration with other dental diagnostic tools.
- Enhance model performance through additional training data.

## Acknowledgments
Special thanks to [Your Institution/Colleagues] for their support and resources.
