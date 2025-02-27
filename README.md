# 🌟 GAN Project Repository

**Description:** A collection of Generative Adversarial Networks (GANs) trained on different datasets.

## 📌 Overview

This repository contains multiple implementations of **Generative Adversarial Networks (GANs)** trained on different datasets. Each project is structured independently, with its own model architecture, training pipeline, and results.

Currently, the repository includes:

- **CIFAR-100 :** Generates synthetic images based on the CIFAR-100 dataset.
- **MNIST :** Generates handwritten digits similar to the MNIST dataset.

More datasets may be added in the future as the research progresses.

---

## 📁 Repository Structure

```
GAN_project/
│── datasets/
│   │── CIFAR-100/
│   │    ├── images/        # Sample generated images
│   │    ├── model/         # Generator & Discriminator models
│   │    ├── training/      # Training scripts & logs
│   │    ├── README.md      
│   │── MNIST/
│   │    ├── images/
│   │    ├── model/
│   │    ├── training/
│   │    ├── README.md  
│── README.md               # General repository overview
```

---

## 📊 Available Projects

### 🖼️ CIFAR-100 GAN

📍 **Dataset:** CIFAR-100\
📍 **Image Size:** `32x32`\
📍 **Classes:** `100`\
📍 **Preprocessing:** Normalized to `[-1,1]`


---

### ✍️ MNIST GAN

📍 **Dataset:** MNIST (Handwritten Digits)\
📍 **Image Size:** `28x28`\
📍 **Classes:** `10`\
📍 **Preprocessing:** Normalized to `[-1,1]`

---

## 📌 Installation & Setup

To run any project in this repository, follow these steps:

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/1sahmuel/GAN-PROJECT.git
```

## 📝 Future Plans

✅ **Add More Datasets**: Extend the repository to include more datasets such as CelebA, Fashion-MNIST, and SVHN.\
✅ **Implement Variants of GANs**: Test Conditional GANs (cGAN), Wasserstein GANs (WGAN), and StyleGANs.\
✅ **Improve Model Performance**: Experiment with hyperparameter tuning, new loss functions, and advanced architectures.

---

## 👨‍💻 Contributing

Contributions are welcome! If you would like to improve this repository:

1. **Fork the repository**
2. **Create a new branch:** `git checkout -b feature-newGAN`
3. **Commit your changes:** `git commit -m "Added new GAN model"`
4. **Push to GitHub:** `git push origin feature-newGAN`
5. **Submit a pull request**

---
