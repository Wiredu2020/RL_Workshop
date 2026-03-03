# RL Workshops 🚀

Personal workshops on **Reinforcement Learning (RL)**, Convolutional Neural Networks (CNN), and computational intelligence, developed through coursework at **LUT** and **AIMS**
 
## Overview

This repository contains notebooks where foundational and advanced concepts in machine learning were explored and implemented, with particular emphasis placed on **Reinforcement Learning** and intelligent agent training methodologies.

---

## 📚 Workshops

### Reinforcement Learning (RL) 🎯

#### RL_workshop1.ipynb
Introduction to Reinforcement Learning fundamentals. Learn how agents interact with environments and basic RL concepts.

#### RL_workshop2.ipynb
**Policy Gradient Methods** - Advanced RL training. Covers:
- CartPole environment with Gymnasium
- Neural network policies
- Policy gradient algorithm
- Custom gradient computation with TensorFlow
- Discount rewards and normalization
- Training loop with adaptive learning

**Requirements:**
- Python 3.7–3.10
- TensorFlow ≥ 2.8.0
- Gymnasium library

---

### Convolutional Neural Networks (CNN)

#### CNN_workshop.ipynb
Working with CNNs for image classification tasks.

#### workshop1.ipynb
Foundational neural network and computer vision concepts.

#### shuffled_pixels_fully_connected.ipynb
Exploring fully connected networks and pixel-level image analysis.

---

## 🛠️ Setup

### Create Virtual Environment

For **RL workshops** (Python 3.10 required):
```powershell
py -3.10 -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

### Install Dependencies
```powershell
pip install -r requirements.txt
```

---

## 📋 Requirements

See `requirements.txt` for all dependencies. Key packages:
- TensorFlow ≥ 2.8.0
- NumPy
- Matplotlib
- Gymnasium (for RL environments)

---

## 🎮 Utilities

### SnakeGame.py
Custom Snake game environment. Used for RL agent training and testing.

---

## 📖 Learning Architecture

The workshop material is structured to progressively build understanding:

- **RL_workshop1.ipynb** — Foundational concepts in reinforcement learning are introduced
- **RL_workshop2.ipynb** — Policy gradient methods are implemented and explored through practical training
- **CNN workshops** — Deep learning foundations and convolutional architectures are examined

Notebooks can be executed through Jupyter:
```powershell
jupyter notebook
```

---

## ✨ Key Topics Covered

**Reinforcement Learning:**
- Agent-environment interaction
- Gymnasium environments (CartPole)
- Policy networks
- Policy gradient training
- Reward discounting and normalization
- Custom TensorFlow training loops

**Deep Learning:**
- Neural network architecture
- CNN fundamentals
- Training and evaluation

---

## 🐍 Python Version

- **RL workshops:** Python 3.7–3.10
- **CNN workshops:** Python 3.7+

---

**References:** Materials adapted from "Hands-On Machine Learning with scikit-learn, keras and tensorflow" (3rd edition) by Aurélien Géron

**Context:** This workshop collection was developed as part of advanced coursework at LUT and AIMS, where deep reinforcement learning methodologies were studied and implemented. The CartPole environment was used as a testbed for exploring policy gradient algorithms and agent learning dynamics.
