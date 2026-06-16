# COVID19-CT-Scan-Detection
Deep learning CNN for automated COVID-19 detection from chest CT scans — 97% accuracy. Built with TensorFlow/Keras
## Problem
Automated detection of COVID-19 from chest CT scan images using a custom CNN — enabling faster, scalable diagnosis support for medical professionals.
 
## Approach
- Built a custom CNN from scratch using Keras with multiple Conv2D, MaxPooling, and Dropout layers
- Applied image augmentation (shear, zoom, horizontal flip) to improve generalization
- Trained on labeled CT scan images split into Train/Validation/Test sets
- Evaluated using confusion matrix, ROC curve, and full classification report
## Results
| Metric | Score |
|--------|-------|
| Accuracy | 97% |
| Precision | 97% |
| Recall | 97% |
| F1-Score | 97% |
 
## Model Architecture
- 4 × Conv2D layers (32 → 64 → 64 → 128 filters)
- MaxPooling + Dropout after each block
- Dense output layer with Sigmoid activation
- Binary classification: COVID-19 vs Normal
## Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- OpenCV
## Dataset
COVID-19 CT Scan Dataset — available on Kaggle  
Organized into Train / Validation / Test directories with COVID and Normal classes.
 
## How to Run
```bash
# Install dependencies
pip install tensorflow keras numpy matplotlib scikit-learn seaborn opencv-python
 
# Open the notebook
jupyter notebook new_data_Set_final_version.ipynb
```
 
## Key Results Visualization
- ROC Curve showing near-perfect classification
- Confusion matrix: 15/15 Normal correct, 14/15 COVID correct
- Classification report with per-class precision, recall, and F1
## Author
Nada Selim — Computer Vision & ML Engineer  
[LinkedIn](https://www.linkedin.com/in/nada-selim-phd-student-a053b5223) | [GitHub](https://github.com/nadaselim-AI)
 
