# 🌾 Rice Plant Disease Detection

## 📌 Problem Statement
This project seeks to accurately classify rice plant diseases using both deep learning and traditional machine learning approaches. By improving early disease detection, this system supports farmers in making timely decisions to prevent crop loss.

## 📊 Dataset Used
- **Source**: [Kaggle - Rice Leaf Diseases](https://www.kaggle.com/datasets/minhhuy2810/rice-leaf-diseases)
- **Classes**: Bacterial Blight, Brown Spot, Leaf Smut
- **Format**: RGB images, resized to 224x224 pixels

---

## 🔍 Experiment Summary

| Model        | Optimizer | Regularization | Dropout | Learning Rate | Early Stopping | Accuracy | F1 Score |
|--------------|-----------|----------------|---------|----------------|----------------|----------|----------|
| Model 1      | Adam      | None           | No      | 0.001          | No             | 32%      | 0.32     |
| Model 2      | Adam      | L2             | No      | 0.001          | No             | 34%      | 0.34     |
| Model 3      | RMSprop   | None           | No      | 0.001          | No             | 31%      | 0.31     |
| Model 4 (Best)| Adam     | L1 + L2        | 0.4     | 0.0003         | Yes            | **33%**  | **0.33** |
| Random Forest| N/A       | N/A            | N/A     | N/A            | N/A            | 81%      | 0.80     |

---

## 📋 Classification Reports

### ✅ Model 1 (Default - Adam, No Reg, No Dropout)
