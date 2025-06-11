# 🏢 Floorgan

**Floorgan** is a Deep Convolutional Generative Adversarial Network (DCGAN) designed to generate architectural floor plans.  
Leveraging deep learning, Floorgan assists architects, designers, and developers in visualizing and prototyping building layouts efficiently.

---

## 📋 Table of Contents

- [🚀 Overview](#-overview)
- [✨ Features](#-features)
- [⚙️ Installation](#-installation-)
- [📖 Usage](#-usage)
- [⚠️ Disclaimer](#-disclaimer)
- [🏗️ Model Architecture](#-model-architecture)
- [🎓 Training](#-training)
- [📊 Evaluation](#-evaluation)

---

## 🚀 Overview

Floorgan utilizes a DCGAN model to generate realistic architectural floor plans. By training on a dataset of existing floor plans, the model learns to produce new designs that adhere to common architectural patterns and layouts.

---

## ✨ Features

- 🔄 **Generative Model:** Produces novel floor plans based on learned distributions.  
- 🧠 **Deep Convolutional Architecture:** Employs convolutional layers for feature extraction and generation.  
- 📐 **Scalability:** Capable of generating floor plans of varying sizes and complexities.  
- ⚙️ **Customizable:** Allows adjustments in model parameters to tailor outputs.

---

## ⚙️ Installation

To get started with Floorgan, clone the repository and install dependencies:

```bash
git clone https://github.com/posilash/floorgan.git
```
---
## 📖 Usage

Run the model using the provided Jupyter Notebook or Google Colab:

`jupyter notebook floorgan.ipynb`

The notebook contains step-by-step instructions on how to train the model, generate floor plans, and visualize results.

---

## ⚠️ Disclaimer

The dataset used to train Floorgan is **not provided** in this repository due to copyright and licensing restrictions.  

This project is intended to serve as a **reference implementation** for generating architectural floor plans using DCGANs.  

Users interested in experimenting with the model should prepare or source their own datasets that comply with all applicable copyright laws and licenses.

---

## 🏗️ Model Architecture

Floorgan's architecture is based on the DCGAN framework, consisting of:

`🏭 Generator: Transforms random noise vectors into floor plan images.`

`🕵️‍♂️ Discriminator: Evaluates the authenticity of generated floor plans.`

Both components are trained adversarially to improve the quality of generated outputs.

## 🎓 Training

To train the model, follow the instructions in the floorgan.ipynb notebook.
Make sure you have a dataset of architectural floor plans in a suitable format (e.g., images or vector graphics). The training process involves:

- 📥 Loading and preprocessing the dataset.

- 🧩 Defining generator and discriminator networks.

- 🔄 Training with adversarial loss functions.

- 📈 Monitoring progress and tuning hyperparameters.

## 📊 Evaluation

After training, evaluate performance by generating new floor plans:

- 🎲 Use the trained generator to produce floor plans from random noise.

- 🔍 Assess quality and diversity of generated plans.

- 📏 Optionally, compare with real floor plans using metrics like Inception Score or Fréchet Inception Distance.

---

## 📚 Credits

This project is inspired by and built upon the principles introduced in the official DCGAN paper:

> **Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks**  
> Alec Radford, Luke Metz, Soumith Chintala (2015)  
> [https://arxiv.org/abs/1511.06434](https://arxiv.org/abs/1511.06434)

Thanks to the original authors for pioneering the DCGAN architecture that makes projects like Floorgan possible.
