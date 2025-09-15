# Autism-Detection
An automated deep learning system for detecting Autism spectrum disorder from images using a fine-tuned Vision Transformer (ViT) model. Built with PyTorch Lightning for structured training, logging, and reproducible evaluation.


# 🧠 Autism Detection Using Vision Transformer (ViT)

## 📌 Overview

This project aims to build an **automated deep learning system** that detects signs of **** from image data.
It leverages a **pre-trained  (ViT)** model, fine-tuned for **binary classification**:

> 🧒 Autistic   vs   🙂 Non-Autistic

The training, validation, and evaluation processes are implemented using the **** framework to ensure clean, reproducible, and scalable experiments.

---

## ⚙️ Features

* Uses transfer learning with ViT for image classification
* Binary classification (Autistic vs Non-Autistic)
* Structured training with PyTorch Lightning
* Accuracy and loss tracking on training, validation, and test sets
* Checkpointing and logging for experiment reproducibility



## 📦 Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Mahwash75/Autism-Detection.git
cd autism-vit
pip install -r requirements.txt
```

---

## 🚀 Usage

Train the model on your dataset:

```bash
python train.py
```

* Logs and checkpoints will be saved automatically.
* Modify hyperparameters and paths in `train.py` as needed.

---


## 📈 Results

The model evaluates its performance using:

* Training/Validation/Test Accuracy
* Training/Validation/Test Loss


