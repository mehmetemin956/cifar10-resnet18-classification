# CIFAR-10 Image Classification with ResNet-18

This project implements a multi-class image classification model using **Transfer Learning (ResNet-18)** on the **CIFAR-10** dataset and deploys it as an interactive web application via **Gradio**.

## Project Overview
- **Task:** Multi-class Image Classification (10 classes)
- **Model Architecture:** Pretrained ResNet-18 (Feature Extraction + Fine-tuned FC Layer)
- **Dataset:** CIFAR-10 (8,000 Train / 2,000 Validation / 2,000 Test)
- **Optimizer & Loss:** AdamW (`lr=1e-3`, `weight_decay=1e-4`), Cross-Entropy Loss
- **Deployment:** Gradio Web Interface

## How to Run
1. Open the `.ipynb` notebook in **Google Colab**.
2. Run all cells sequentially to train the model, evaluate test metrics, and launch the Gradio interface.
3. Upload an image through the Gradio UI to get Top-3 class predictions.
