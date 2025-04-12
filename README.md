# 🍎 King of Fruits – Fruit & Color Classification using ResNet50

This project builds an image classifier using **ResNet50**, a deep pretrained **Convolutional Neural Network (CNN)**, to predict **fruit type and color** from image data.  
Examples: 🍏 Green Apple, 🍎 Red Apple, 🍊 Orange, 🥭 Yellow Mango, etc.

![Project](https://img.shields.io/badge/Project-King%20of%20Fruits-orange?style=flat)
![Model](https://img.shields.io/badge/Model-ResNet50-blue?style=flat)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-lightgrey?style=flat)
![Type](https://img.shields.io/badge/Type-Multiclass%20Image%20Classification-green?style=flat)

---

## 🚀 Project Overview

- 📂 **Input**: Fruit images labeled by folder structure
- 🔍 **Target**: Combined fruit type + color
- 🧠 **Model**: ResNet50 (pretrained on ImageNet)
- 🔧 **Modifications**: Custom dense layers on top for fine-tuning
- 📊 **Evaluation**: Accuracy, Confusion Matrix, Classification Report
- 🧪 **Tools**: TensorFlow, Keras, NumPy, PIL, Matplotlib, Seaborn

---

## 🧠 Workflow

```text
📁 Dataset
 ┣ RedApple/
 ┣ GreenApple/
 ┣ YellowMango/
 ┗ ...

🔍 EDA
 ┗ Visualize image distribution

🧹 Preprocessing
 ┣ Resize, normalize images
 ┣ Convert to arrays, encode labels

🧠 Modeling
 ┣ Load ResNet50 (without top)
 ┣ Add custom dense layers
 ┣ Compile & train model

📊 Evaluation
 ┣ Accuracy/loss curve
 ┣ Confusion matrix
 ┣ Visual prediction samples
```

---

## 📊 Evaluation Sample

| Metric     | Value (example) |
|------------|------------------|
| Accuracy   | ~92%             |
| Classes    | 8+ combinations  |
| Model Type | ResNet50 CNN     |

---

## 📂 Project Structure

```
📦 king-of-fruits
 ┣ 📄 KingofFruits.ipynb
 ┣ 📄 README.md
 ┗ 📁 dataset/
     ┗ [fruit]/[images].jpg
```

---

## 👨‍💻 Author

**Indra Eka Mandriana S.Kom**  
_Machine Learning Engineer_  
[LinkedIn](https://www.linkedin.com/in/indra-eka-mandriana-47a885148/) | [GitHub](https://github.com/indraekam)

---

## ⭐ If you find this useful, star the repo!
