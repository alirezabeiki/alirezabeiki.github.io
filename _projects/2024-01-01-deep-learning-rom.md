---
title: "Deep Learning-based Reduced Order Modeling (ROM)"
collection: projects
type: 'project'
permalink: /projects/deep-learning-rom
excerpt: 'A test project exploring the application of deep learning techniques, specifically Convolutional Autoencoders and LSTMs, for Reduced Order Modeling of complex fluid dynamics systems.'
date: 2024-01-01
location: 'Shiraz, Iran'
tags:
  - Deep Learning
  - Reduced Order Modeling
  - Fluid Dynamics
  - Autoencoders
  - Python
---

## 🚀 Project Overview

This is a test project page demonstrating the integration of Deep Learning with Reduced Order Modeling (ROM). The primary goal of this project is to develop a data-driven framework capable of accurately predicting the spatiotemporal evolution of complex fluid flows with significantly lower computational costs compared to traditional CFD solvers.

## 🌟 Key Features

*   **High-Fidelity Reconstruction:** Utilizes advanced Convolutional Autoencoders (CAE) to compress high-dimensional flow fields into a low-dimensional latent space.
*   **Temporal Forecasting:** Employs recurrent neural networks (like ConvLSTM or GRU) to predict the future states of the flow in the latent space.
*   **Attention Mechanisms:** Integrates novel attention blocks to dynamically capture critical flow features (e.g., vortex shedding, wake dynamics).
*   **Computational Efficiency:** Achieves real-time or faster-than-real-time predictions for parametric studies and control applications.

## ️ Methodology

1.  **Data Generation:** High-fidelity data is generated using Direct Numerical Simulation (DNS) or Large Eddy Simulation (LES) for benchmark cases (e.g., flow over a cylinder, dam break).
2.  **Spatial Compression:** A CAE is trained to map the 2D/3D flow fields (velocity, pressure) to a compact latent representation.
3.  **Time Evolution:** A sequence-to-sequence model forecasts the latent variables over time.
4.  **Reconstruction:** The decoder maps the predicted latent variables back to the physical space.

## 📊 Visualizations

*(Placeholder for images and videos. You can replace these with actual links or local files in your `images/` folder.)*

### Flow Field Reconstruction
![ROM Reconstruction](https://via.placeholder.com/800x400?text=Flow+Field+Reconstruction+Comparison)
*Figure 1: Comparison between High-Fidelity CFD (Ground Truth) and Deep Learning ROM predictions.*

### Dynamic Feature Capturing
<iframe width="100%" height="400" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
*Video 1: Demonstration of the latent space dynamics and flow reconstruction over time.*

## 💻 Code & Resources

The source code for this project is available on GitHub. 

- **GitHub Repository:** [Link to your repo](https://github.com/alirezabeiki)
- **Framework:** PyTorch / TensorFlow
- **Dependencies:** `numpy`, `scipy`, `matplotlib`, `torch`

### Quick Start
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
pip install -r requirements.txt
python main.py --config config.yaml