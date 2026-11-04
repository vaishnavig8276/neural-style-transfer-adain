# 🎨 neural-style-transfer-adain

PyTorch implementation of fast neural style transfer using Adaptive Instance Normalization (AdaIN) with a pre-trained VGG encoder[cite: 2].

This project allows you to apply the artistic style of one image (the style image) to another image (the content image) in real-time, completely transforming its visual appearance while preserving the original structure.

## ✨ Features
* **Fast Style Transfer:** Leverages the AdaIN layer to align the mean and variance of content features with style features, eliminating the need for a lengthy optimization process.
* **Pre-trained VGG Encoder:** Uses a robust VGG network to extract high-level feature maps[cite: 2].
* **Flexible Stylization:** Easily adjust the alpha parameter to control the blend weight between the original content and the applied style.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** PyTorch, Torchvision
* **Data Processing:** OpenCV, NumPy

## 📂 Dataset
This model was trained and evaluated using the NovaGen dataset. You can download the complete dataset resources here:

[![NovaGen dataset](https://img.shields.io/badge/NovaGen_dataset-6C75D1?style=for-the-badge&logo=download&logoColor=white)](#link-to-your-dataset)
*(Replace `#link-to-your-dataset` with your actual download link)*

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/vaishnavig8276/neural-style-transfer-adain.git](https://github.com/vaishnavig8276/neural-style-transfer-adain.git)
cd neural-style-transfer-adain


