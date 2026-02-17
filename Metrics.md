# Medical Image Classification Training Report

## Training Loss over Epochs
- **Epoch 1**: Loss = 0.9926
- **Epoch 2**: Loss = 0.6598
- **Epoch 3**: Loss = 0.4764
- **Epoch 4**: Loss = 0.3652
- **Epoch 5**: Loss = 0.2997

## Final Validation Metrics
- **Final Validation Accuracy**: 86.71%

## Classification Report
| Class     | Precision | Recall | F1 Score | Support |
|-----------|-----------|--------|----------|---------|
| Benign    | 0.89      | 0.92   | 0.91     | 201     |
| Malignant | 0.77      | 0.71   | 0.74     | 66      |
| Normal    | 0.88      | 0.86   | 0.87     | 49      |

## Code Optimization Recommendations
- Update from `torch.cuda.amp.autocast()` to `torch.amp.autocast('cuda')`

## Grad-CAM Visualization
- Description of the benign ultrasound image showing light-blue mask in ROI.

*This report outlines the training process and results for the medical image classification model.*
