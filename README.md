# ⚡ GANs with PyTorch

<div align="center">

**Understanding and implementing Generative Adversarial Networks using PyTorch.**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-Generative_AI-blueviolet?style=flat-square)

</div>

## 🧠 About

A hands-on learning project exploring two fundamental Generative Adversarial Network architectures using PyTorch and the CelebA dataset.

## 🚀 Implementations

### 1. Vanilla GAN
- Uses fully connected neural networks.
- **Generator:** Converts random noise into synthetic images.
- **Discriminator:** Classifies images as real or fake.
- Both networks compete through adversarial training.

<text>**Status:** ✅ Implemented</text>

### 2. DCGAN (Deep Convolutional GAN)
- Uses convolutional neural networks for image generation.
- **Generator:** Uses Transposed Convolutional layers to generate images.
- **Discriminator:** Uses Convolutional layers to classify real and fake images.
- Learns spatial features to generate more realistic images.

<text>**Status:** 🔄 In Progress</text>

## 🔄 Working Flowcharts
![Vanilla GAN and DCGAN Working Flow](images/gan_workflow.png)
The infographic below illustrates the complete working and training flow of both architectures.

![Vanilla GAN and DCGAN Working Flow](images/gan_workflow.png)

## 🛠️ Tech Stack

Python • PyTorch • Torchvision • NumPy • Matplotlib • Google Colab

## 📊 Dataset

**CelebA** – 202,599 celebrity face images used for image generation experiments. Dataset is not included in this repository.

---

<div align="center">

**Learn • Build • Experiment • Generate**

</div>
