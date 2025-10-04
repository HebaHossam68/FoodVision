# 🍕🥩🍣 FoodVision – Classifying Pizza, Steak, and Sushi with PyTorch

This project demonstrates how to build and compare deep learning models for **food image classification** using **PyTorch**.  
We trained and evaluated two different models on the `pizza-steak-sushi` dataset and deployed the best one with a **Gradio web app**.

---

## 🚀 Project Overview

1. **Dataset**  
   - `pizza-steak-sushi` dataset (3 classes).
   - Split into `train/` and `test/` folders.

2. **Models**  
   - **EfficientNet-B0 (torchvision)** → achieved **~89% test accuracy**.  
   - **Vision Transformer (ViT, Hugging Face)** → achieved **~97% test accuracy**.

3. **Deployment**  
   - The ViT model was deployed using a **Gradio app** for real-time predictions.  
   - Users can upload an image of pizza, steak, or sushi, and the model predicts the class with probabilities.

---

## 🧑‍💻 Tech Stack

- **PyTorch** → model training and evaluation  
- **Torchvision** → EfficientNet-B0 backbone  
- **Hugging Face Transformers** → Vision Transformer (ViT)  
- **Albumentations** → image augmentations  
- **Gradio** → deployment with a simple web interface  
- **TensorBoard** → training monitoring and visualization  

---

## 📊 Results

| Model            | Test Accuracy |
|------------------|--------------|
| EfficientNet-B0  | **89%**      |
| ViT (Hugging Face) | **97%**    |

✅ ViT clearly outperformed EfficientNet on this dataset.


