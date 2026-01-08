# Banana Leaf Disease Classification using Deep Learning

This project presents a deep learning–based system for automated classification of banana leaf diseases using convolutional neural networks.

## Diseases Classified
- Healthy
- Cordana
- Sigatoka
- Pestalotiopsis

## Methodology
- Dataset prepared and split into training, validation, and test sets
- Data augmentation applied to improve generalization
- Transfer learning using EfficientNetB0 pre-trained on ImageNet
- Fine-tuning of higher convolutional layers
- Evaluation using accuracy, confusion matrix, and classification report

## Model
- Architecture: EfficientNetB0
- Framework: TensorFlow / Keras
- Input Size: 224 × 224 RGB images
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy

## Results
- Test Accuracy: **95.31%**
- High recall across disease classes
- Minimal overfitting observed

## Files
- `Banana_Leaf_Disease_Classification.ipynb` – Complete training and evaluation notebook

## Note
The trained model file (`.keras`) and full dataset are not included in this repository due to size constraints.
