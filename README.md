# Controllable High-Quality Image Generation

This repository contains the implementation and experiments for the course project **“Towards Controllable High-Quality Image Generation.”**  
The project explores improving both **image quality** and **fine-grained control** in generative models by combining insights from VAEs, GANs, and contrastive learning.

---

## 📌 Overview
Generative models like VAEs, GANs, and Diffusion models have achieved impressive quality but often lack **controllability** in their latent spaces.  
This project surveys advanced architectures and implements methods to enhance controllability while preserving fidelity.

Key areas explored:
- Variational Autoencoders (VAEs) and extensions (DiffuseVAE, NoisyVAE).  
- Generative Adversarial Networks: GAN, Conditional GAN, ContraGAN, StyleGAN.  
- Latent-space manipulation using PCA and contrastive losses.

---

## ✍️ My Contributions
- **Surveyed** literature on **GANs, Conditional GANs, and ContraGAN**, analyzing techniques for controllable image generation.  
- **Implemented** a **Contrastive VAE** with contrastive loss (inspired by ContraGAN) to improve **latent space disentanglement**.  
- **Developed** a **Conditional GAN** for class-controlled image generation on **MNIST**, enabling attribute-level control.  

---
## 📊 Results
- **Contrastive VAE** produced more **separated and interpretable latent vectors** compared to standard VAE.  
- **Conditional GAN** generated sharp, class-specific MNIST digits with stable training.  
- Demonstrated controllable manipulations (e.g., stroke thickness, position) in latent space.

---

## 👥 Team
- Rajiv Chitale  
- Vedant Bhandare  
- Umanshiva Ladva  
- Nitya Bhamidipaty

---
