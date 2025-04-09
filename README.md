## Animal Image Classifier — PyTorch V1

This is a simple, educational project that demonstrates how to build a grayscale image classifier using PyTorch. The model classifies synthetic 28x28 images into three classes: cats, dogs, and raccoons.

The idea is to start small and use this to learn basic PyTorch concepts like:
- Tensor operations
- Model building using `nn.Module`
- Training loop (forward, loss, backward, optimizer)
- Accuracy metrics
- Validation and testing

This project was created by [Geeta Kudumula](https://www.linkedin.com/in/geetakudumula) as part of a practical AI learning path.

---

##  Tools & Frameworks
- Python 3.8+
- PyTorch
- NumPy
- Jupyter Notebook

---

## Model Overview

Input: 28x28 grayscale image  
Layers:
- Flatten
- Linear (128, ReLU)
- Linear (64, ReLU)
- Linear (3, Softmax)

---

##  Project Files

| File                    | Description                                  |
|-------------------------|----------------------------------------------|
| animal_classifier_v1.ipynb | Jupyter Notebook for training and evaluation |
| README.md               | Project notes and explanation                |

---

##  Sample Output
Test Image 1: Predicted as 'Cat' with 0.54 confidence 
Test Image 2: Predicted as 'Dog' with 0.49 confidence 
Test Image 3: Predicted as 'Raccoon' with 0.58 confidence


---

##  Why I Built This

As someone with experience in cloud, streaming, and data architecture, I’m expanding into AI by practicing end-to-end model development and inference using different ML frameworks.

---

##  What’s Next (V2 Ideas)

- Use real-world datasets like CIFAR-10
- Add image augmentation and transforms
- Save and load the model for inference
- Add torchmetrics and tensorboard logging
- Try deploying using Flask or Streamlit

---

##  Author

Created by Geeta Kudumula  
AI/ML + Cloud Solutions Architect

---
 Found this useful? Give it a star and follow along as I continue learning and building!



