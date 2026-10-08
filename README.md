# RA Hand X-ray Severity Grading

A deep learning project for grading **Rheumatoid Arthritis (RA) severity from hand X-ray images** into three classes:

- Mild
- Moderate
- Severe

## Dataset

Rheumatoid Arthritis Detection Dataset from Kaggle:

https://www.kaggle.com/datasets/sindhuvunna/rheumatoid-arthritis-detection

## Methodology

1. CLAHE image preprocessing
2. EfficientNet-B0 backbone
3. CBAM attention mechanism
4. CORAL ordinal classification
5. Conformal prediction for confidence-based deferral
6. Grad-CAM++ for explainability
7. Optional Vision-Language Model reporting

### Workflow

```text
X-ray Image
     ↓
CLAHE Preprocessing
     ↓
EfficientNet-B0
     ↓
CBAM Attention
     ↓
CORAL Ordinal Classifier
     ↓
Mild / Moderate / Severe
     ↓
Conformal Prediction
     ↓
Grad-CAM++ Explanation
```

## Evaluation

- Accuracy
- Macro-F1
- Balanced Accuracy
- QWK
- MAE
- Confusion Matrix
- Within-One-Grade Accuracy

## Technologies

Python • PyTorch • Torchvision • OpenCV • Scikit-learn • Grad-CAM++

## Disclaimer

This project is for **research and educational purposes only**. It is not a medical diagnostic system and should not replace assessment by a qualified healthcare professional.
