# 🌸 Iris Flower Classification using Neural Networks

This project implements a simple **feedforward neural network** in PyTorch to classify the famous **Iris dataset** into three species:
- Setosa
- Versicolor
- Virginica  

The model achieves a **final loss of 0.039** after training for **100 epochs**.

---

## 📊 Dataset
The Iris dataset consists of:
- **150 samples**  
- **4 features** (sepal length, sepal width, petal length, petal width)  
- **3 target classes** (Setosa, Versicolor, Virginica)  

It is widely used as a beginner-friendly dataset for machine learning.

---

## 🧠 Model Architecture
- **Input layer**: 4 neurons (one per feature)  
- **Hidden Layer 1**: 8 neurons, ReLU activation  
- **Hidden Layer 2**: 9 neurons, ReLU activation  
- **Output layer**: 3 neurons (one per class, with Softmax activation)  

---

## ⚙️ Training Setup
- **Framework**: PyTorch  
- **Loss function**: CrossEntropyLoss  
- **Optimizer**: Adam  
- **Learning rate**: `0.01`  
- **Epochs**: 100  

---

## 📈 Results
- **Final Loss**: `0.039`  
- **Accuracy**: ~97–100% (depending on random seed)  

The low loss indicates that the model is able to learn the patterns in the dataset effectively.

---
