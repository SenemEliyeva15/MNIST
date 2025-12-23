# MNIST
MNIST
# Task [X]: [Task Name]

**Student:**  Senem 
**ID:** S201  
**Seed:** 20240201

## Presentation
[View Presentation Slides](https://drive.google.com/your-link-here)

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
- **Test accuracy:** 99.29%

### Version 2
- **Learning rate:** 0.0001
- **Batch size:** 64
- **Optimizer:** SGD with momentum=0.9
- **Test accuracy:** 99.00%

### Best Result
- **Best version:** Version 1
- **Final test accuracy:** [X.XX]%
- **Target accuracy:** [X.XX]%
- **Status:** ✓ Achieved / ✗ Below target

## Analysis
- **Best performing class:** [class name]
- **Worst performing class:** [class name]
- **Key observations:** [2-3 sentences about what you learned]

## Files
- `notebook.ipynb`: [Untitled3.ipynb](https://github.com/user-attachments/files/24317700/Untitled3.ipynb)
- `results/training_comparison.png`: Comparison of Version 1 vs Version 2
- `results/confusion_matrix.png`: Confusion matrix from best model
- `results/predictions.png`: Sample predictions
