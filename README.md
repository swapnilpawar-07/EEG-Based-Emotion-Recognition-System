# EEG-Based Emotion Recognition System

A deep learning-based **EEG emotion recognition system** that leverages **Semi-Supervised Learning**, **Variational Autoencoders (VAEs)**, and **Recurrent Neural Networks (RNNs)** to classify emotional states from multi-channel EEG signals. The model learns meaningful latent representations from both labeled and unlabeled EEG data, improving classification performance while reconstructing EEG signals for robust feature learning.

---

## Overview

Emotion recognition from EEG signals is a challenging task due to the high dimensionality, temporal dependencies, and limited availability of labeled data. This project addresses these challenges by combining **Variational Autoencoders (VAEs)** for unsupervised feature learning with **Recurrent Neural Networks (RNNs)** for modeling temporal dynamics in EEG recordings.

The semi-supervised architecture enables the model to effectively utilize both labeled and unlabeled EEG data, resulting in improved generalization and more robust emotion classification.

---

## Features

- **EEG Data Preprocessing**
  - Normalize multi-channel EEG signals for stable and efficient model training.

- **Semi-Supervised Learning**
  - Leverage unlabeled EEG data to improve feature representation and classification performance.

- **Variational Autoencoder (VAE)**
  - Learn compact latent representations while reconstructing EEG signals.

- **Recurrent Neural Networks (RNNs)**
  - Capture temporal dependencies within sequential EEG recordings.

- **Emotion Classification**
  - Predict emotional states from learned latent features.

- **Signal Reconstruction**
  - Compare original and reconstructed EEG signals to evaluate representation quality.

- **Visualization Tools**
  - Generate visualizations for EEG signals, latent features, training performance, and reconstruction quality.

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Deep Learning | TensorFlow / Keras |
| Model Architecture | Variational Autoencoder (VAE), Recurrent Neural Network (RNN) |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |

---

## Model Architecture

The proposed framework consists of three major stages:

1. **Data Preprocessing**
   - EEG normalization
   - Data preparation
   - Sequence generation

2. **Feature Learning**
   - Variational Autoencoder learns compact latent representations
   - Reconstruction loss encourages meaningful feature extraction

3. **Emotion Classification**
   - RNN processes latent sequences
   - Predicts emotional states based on learned temporal patterns

---

## Key Features Learned

- Temporal EEG signal representation
- Latent feature extraction
- Semi-supervised representation learning
- Emotion classification from brain signals
- EEG signal reconstruction

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/eeg-emotion-recognition.git
cd eeg-emotion-recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the complete pipeline:

```bash
python main.py
```

The pipeline performs:

- EEG data preprocessing
- Model training
- Emotion classification
- Signal reconstruction
- Visualization of results

---

## Dataset

Due to privacy and licensing restrictions, the EEG dataset used in this project cannot be distributed publicly.

The dataset consists of:

- Multi-channel EEG recordings
- Emotion annotations
- Sequential brain activity signals

Users can evaluate the system using their own EEG dataset by following the expected data structure used within the project.

---

## Learning Outcomes

This project provided practical experience in:

- EEG signal processing
- Semi-supervised deep learning
- Variational Autoencoders (VAEs)
- Recurrent Neural Networks (RNNs)
- Time-series modeling
- Emotion recognition
- Representation learning
- Neural signal reconstruction

---
- Multi-modal emotion recognition using EEG and physiological signals
- Real-time emotion prediction
- Deployment as an interactive emotion recognition application
