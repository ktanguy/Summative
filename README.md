# 🌾 Rice Plant Disease Detection

## 📌 Problem Statement
This project seeks to accurately classify rice plant diseases using both deep learning and traditional machine learning approaches. By improving early disease detection, this system supports farmers in making timely decisions to prevent crop loss.

## 📊 Dataset Used
- **Source**: [Kaggle - Rice Leaf Diseases](https://www.kaggle.com/datasets/minhhuy2810/rice-leaf-diseases)
- **Classes**: Bacterial Blight, Brown Spot, Leaf Smut
- **Format**: RGB images, resized to 224x224 pixels

---

## 🔍 Experiment Summary
| Model No. | Optimizer | Regularizer | Epochs | Early Stopping | # Layers | Learning Rate | Accuracy | F1 Score | Recall | Precision |
| --------- | --------- | ----------- | ------ | -------------- | -------- | ------------- | -------- | -------- | ------ | --------- |
| Model 1   | Adam      | None        | 10     | No             | 3        | 0.001         | 0.32     | 0.32     | 0.32   | 0.32      |
| Model 2   | Adam      | L2          | 10     | Yes            | 3        | 0.001         | 0.34     | 0.34     | 0.34   | 0.34      |
| Model 3   | RMSprop   | None        | 10     | No             | 3        | 0.001         | 0.31     | 0.31     | 0.31   | 0.31      |
| Model 4   | Adam      | L2          | 10     | Yes            | 3        | 0.0005        | 0.33     | 0.33     | 0.33   | 0.33      |

---

## 📋 Classification Reports

### ✅ Model 1 (Default - Adam, No Reg, No Dropout)
