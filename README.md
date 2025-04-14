# :star: Colorization-CNN-ResNetV2

![resnet50](https://img.shields.io/badge/model-ResNet50-blue) 

## 📌 Project Overview
This project tackles the problem of **Colorization** using deep learning. We utilize a **Combine** model (CNN and Inception-ResNetV2) to colorize black and white **Fruit Photos**

> 📍 Approach & model structure: [Research paper](https://arxiv.org/pdf/1712.03400v1.pdf)
> 📍 Reference: [View here]( https://github.com/saeed-anwar/ColorSurvey#dataset)
> 📍 Kaggle notebook: [View here](https://www.kaggle.com/code/tantranduc/colorization-cnn-resnetv2)  
> 📍 Dataset used: [Link to dataset](https://www.kaggle.com/code/tantranduc/colorization-cnn-resnetv2)

---

## 🚀 Tech Stack

- Python
- TensorFlow / Keras
- ResNet50 (transfer learning)
- NumPy, Pandas, Matplotlib
- Scikit-learn

---

## 🧠 Model Approach

1. **Data Preprocessing**:
   - Resized all images to `224x224` and `299x299` 
   - Convert Image from RGB to LAB formula 
   - Applied data augmentation: rotation, zoom, flips
   - Normalized pixel values

2. **Model**:
   - View at **Approach & model structure**

3. **Evaluation**:
   - Accuracy: **55%**
## 📊 Results

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | 55%       |

---

## 🧰 How to Run

```bash
mkdir colorization && cd colorization
git clone https://github.com/tantran1011/Colorization-CNN-ResNetV2.git

# Open the notebook
jupyter notebook colorization-cnn-resnetv2.ipynb
