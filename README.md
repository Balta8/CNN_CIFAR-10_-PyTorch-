readme_content = """# CIFAR-10 Image Classification (PyTorch)

This project trains a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the **CIFAR-10 dataset** into 10 categories.

---

## ⚙️ Requirements
```bash
pip install torch torchvision matplotlib scikit-learn

## 🧠 Model Architecture
Conv2d (3 → 32) + BatchNorm + ReLU + MaxPool
Conv2d (32 → 64) + BatchNorm + ReLU + MaxPool
Fully Connected (4096 → 512) + Dropout(0.5) + ReLU
Fully Connected (512 → 10)

## 📊 Results
Expected test accuracy: 70–75% after 10 epochs
Accuracy can be improved with data augmentation and deeper models
