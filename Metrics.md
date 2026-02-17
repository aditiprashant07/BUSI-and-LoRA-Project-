# Medical Image Classification Training Report

## Training Loss over Epochs
- **Epoch 1**: Loss = 0.9085303518591048
- **Epoch 2**: Loss = 0.651981007732168
- **Epoch 3**: Loss = 0.4881929002607925
- **Epoch 4**: Loss = 0.3654937744140625
- **Epoch 5**: Loss = 0.29235759264306177

## Final Validation Metrics
- **Final Validation Accuracy**: 85.44303797468355 %

## Classification Report
| Class     | Precision | Recall | F1 Score | Support |
|-----------|-----------|--------|----------|---------|
| Benign    |0.88      |0.88      |0.88       |174  |
| Malignant |0.84      |0.79      |0.82        |96    |
| Normal    |0.79      |0.89      |0.84       | 46     |

## Code Optimization Recommendations
- Update from `torch.cuda.amp.autocast()` to `torch.amp.autocast('cuda')`

## Grad-CAM Visualization
- Benign
  <img width="1694" height="761" alt="Screenshot 2026-02-17 134310" src="https://github.com/user-attachments/assets/b2e6dff7-58f1-40be-becc-9a6f84c0c721" />

- Malignant
  <img width="1636" height="763" alt="Screenshot 2026-02-17 134318" src="https://github.com/user-attachments/assets/267bd41d-4b79-4ff2-ad8c-308ba1a834e0" />

- Normal 
<img width="1616" height="760" alt="Screenshot 2026-02-17 134326" src="https://github.com/user-attachments/assets/e759fcc9-4e42-4a04-950e-5b3ccb5e29f0" />




*This report outlines the training process and results for the medical image classification model.*
