# 🌾 Rice Plant Disease Detection

## 📌 Problem Statement
This project seeks to accurately classify rice plant diseases using both deep learning and traditional machine learning approaches. By improving early disease detection, this system supports farmers in making timely decisions to prevent crop loss.

## 📊 Dataset Used
- **Source**: [Kaggle - Rice Leaf Diseases](https://www.kaggle.com/datasets/minhhuy2810/rice-leaf-diseases)
- **Classes**: Bacterial Blight, Brown Spot, Leaf Smut
- **Format**: RGB images, resized to 224x224 pixels

---

| Model No. | Optimizer | Regularizer | Epochs | Early Stopping | # Layers | Learning Rate | Accuracy | F1 Score | Recall | Precision |
| --------- | --------- | ----------- | ------ | -------------- | -------- | ------------- | -------- | -------- | ------ | --------- |
| Model 1   | Adam      | None        | 10     | No             | 3        | 0.001         | 0.35     | 0.35     | 0.35   | 0.35      |
| Model 2   | Adam      | L2          | 15     | Yes            | 3        | 0.001         | 0.34     | 0.34     | 0.34   | 0.34      |
| Model 3   | RMSprop   | None        | 5      | No             | 3        | 0.001         | 0.34     | 0.34     | 0.34   | 0.34      |
| Model 4   | Adam      | L2          | 5      | Yes            | 3        | 0.0005        | 0.36     | 0.36     | 0.36   | 0.36      |


---

## 📋 Classification Reports
The link of the models it exceeded the mbs of github it couldn’t be pushed 

- https://drive.google.com/drive/folders/1YVNFcLJP_IUYAUnsResAwWWWR8IctRi0?usp=drive_link

- Link to the video : https://drive.google.com/file/d/15aL2PuwEkhrsVhDDBoRVY-FKPtSjNH87/view?usp=drive_link

