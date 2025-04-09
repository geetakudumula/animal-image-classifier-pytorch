🧠 Animal Image Classifier — PyTorch V1

This is a simple, educational project that demonstrates how to build a grayscale image classifier using PyTorch. The model classifies synthetic 28x28 images into three classes: cats, dogs, and raccoons.

The idea is to start small and use this to learn basic PyTorch concepts like:
- Tensor operations
- Model building using `nn.Module`
- Training loop (forward, loss, backward, optimizer)
- Accuracy metrics
- Validation and testing

✅ This project was created by [Geeta Kudumula](https://www.linkedin.com/in/geetakudumula) as part of a practical AI learning path.

---

## 🛠️ Tools & Frameworks
- Python 3.8+
- PyTorch
- NumPy
- Jupyter Notebook

---

## 🧱 Model Overview

Input: 28x28 grayscale image  
Layers:
- Flatten
- Linear (128, ReLU)
- Linear (64, ReLU)
- Linear (3, Softmax)

---

## 📂 Project Files

| File                    | Description                                  |
|-------------------------|----------------------------------------------|
| animal_classifier_v1.ipynb | Jupyter Notebook for training and evaluation |
| README.md               | Project notes and explanation                |

---

## 🖼️ Sample Output

