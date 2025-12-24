# MNIST
MNIST
# Task 1: MNIST

**Student:**  Senem 
**ID:** S201  
**Seed:** 20240201

## Presentation
[View Presentation Slides] (https://docs.google.com/presentation/d/1Wp-XTYuzGIpE6DmkjwylJYcA3k7uOliN/edit?usp=drive_link&ouid=108242459376067484421&rtpof=true&sd=true)

## Dataset
- **Name:** MNIST
- **Classes:** 10
- **Training samples:** 60000
- **Test samples:** 10000

## Model Architecture
- **Type:** [CNN/ResNet18/MobileNetV2]
- **Convolutional layers:** 2
- **Fully connected layers:** 2
- **Total parameters:** 421,642

## Training Comparison

### Version 1
- **Learning rate:** 0.001
- **Batch size:** 32
- **Optimizer:** Adam
- **Test accuracy:** 99.31%

### Version 2
- **Learning rate:** 0.0001
- **Batch size:** 64
- **Optimizer:** SGD with momentum=0.9
- **Test accuracy:** 98.91%

### Best Result
- **Best version:** Version 1
- **Final test accuracy:** 99.31%
- **Target accuracy:**≥88%
- **Status:** ✓ Achieved 

## Analysis
- **Best performing class:** 1
- **Worst performing class:** 5
- **Key observations:**The incorrect predictions mainly occurred between the digits 4 and 9, which are visually very similar to each other. Since MNIST is a simple dataset, the model converged very quickly with a learning rate of 0.001, easily exceeding the target accuracy.

## Files
- `notebook.ipynb`: [Untitled3_(2) (1).ipynb](https://github.com/user-attachments/files/24331668/Untitled3_.2.1.ipynb)
- `results/training_comparison.png`: Comparison of Version 1 vs Version 2
- `results/confusion_matrix.png`: Confusion matrix from best model
- `results/predictions.png`: Sample predictions
