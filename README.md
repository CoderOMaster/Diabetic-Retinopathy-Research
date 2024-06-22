
---

# Diabetic Retinopathy Detection

## Overview
This project aims to segment blood vessels in retinal images, which will be further used to detect anomalies associated with diabetic retinopathy and other ocular diseases. The project is an ongoing research initiative.

## Project Description
### Objectives
- Segment blood vessels in retinal images.
- Detect anomalies for diabetic retinopathy and other diseases.

### Methodology
1. **U-Net Implementation**
   - Implemented U-Net with ResNet34 and EfficientNet-B7 encoders.
   - Achieved 96% accuracy and 98% specificity using the DRIVE dataset of 20 images.
   - Tested several other encoders, including Inception and Xception, but ResNet34 and EfficientNet-B7 provided the best results.

2. **GAN Implementation**
   - Developed a PIX2PIX GAN with U-Net and U-Net++ generators independently.
   - Utilized the FIVES dataset comprising over 600 images to generate highly accurate masks for fundus images.
   - Aimed to test over larger datasets.
   - Currently exploring other models like U-Net++, U-Net Square, and other variations of U-Net.

### Current Status
- The project is at the moment confidential and the code will remain private until the research paper is published due to medical privacy concerns.

## Future Work
- Expand testing to larger datasets.
- Implement and evaluate additional models like U-Net++, U-Net Square, and other U-Net variations.

## Contact
For further information or queries, please contact the project team.
EMAIL: keshavarorasci@gmail.com
---

