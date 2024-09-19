
# Brain Tumor Segmentation using CNN 🧠

## Overview
This project focuses on detecting brain tumors using Convolutional Neural Networks (CNN) for medical image analysis. MRI scans are utilized as the primary input for training the model to identify the presence of brain tumors.

## Motivation
The use of AI in the medical field, particularly for diagnosing conditions such as brain tumors, has significantly improved accuracy and reduced errors due to human judgment. This project employs a CNN-based approach to assist radiologists in detecting tumors from MRI scans, reducing time and increasing diagnostic accuracy.

## Dataset 📊
- **Source**: Kaggle
- **Images**: 253 MRI images
  - 98 images labeled as "No Tumor"
  - 155 images labeled as "Tumor"

## Model Architecture 🧠
The project uses a pre-trained **VGG-16** model with transfer learning to detect tumors in the MRI scans. The model's architecture is extended with additional layers, including dense and dropout layers, to adapt to the specific classification task.

### Data Augmentation Techniques:
- Rotation
- Rescaling
- Brightness adjustments
- Horizontal and vertical flips

## Methodology
The key steps followed in this project:
1. **Preprocessing**: Images are resized and augmented to increase the dataset size and improve model robustness.
2. **Model Building**: The pre-trained VGG-16 model is fine-tuned with transfer learning, adding custom layers to adapt to our binary classification task.
3. **Training**: The model is trained with a binary cross-entropy loss function and evaluated on both validation and test sets.
4. **Evaluation**: Accuracy and loss are evaluated across epochs, and a confusion matrix is generated to observe performance.

## Results 📈
- **Validation Accuracy**: 92%
- **Test Accuracy**: 80%
- **Test Sensitivity & Specificity**: 80%

The model shows promising results for detecting brain tumors with high accuracy. The performance can further improve with larger datasets and additional fine-tuning.

## Future Work 🔮
- Implementing additional architectures such as ResNet or InceptionNet for further performance improvements.
- Incorporating larger and more diverse datasets to improve model generalizability.

## Contributors 👥
- **Arya Goyal** (aryagoyal1301@gmail.com)
- **Saumya Pandey** (saumyapandeycse@gmail.com)
- **D. Vansuha** (vanushad@srmist.edu.in)

---
