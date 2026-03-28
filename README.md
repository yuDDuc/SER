# Speech Emotion Recognition (SER) Analysis

![SER Header](https://raw.githubusercontent.com/username/SER/main/assets/header.png)

## Overview
This project implements a **Speech Emotion Recognition (SER)** system using Deep Learning. It evaluates multiple model architectures (Baseline, Dropout, Batch Normalization, L2 Regularization) and Data Augmentation techniques to classify emotions from audio signals.

## Datasets
- **RAVDESS**: Ryerson Audio-Visual Database of Emotional Speech and Song.
- **EmoDB**: Berlin Database of Emotional Speech.
- *Emotions considered*: Angry, Sad, Fear, Happy, Neutral, Disgust.

## Performance Results
| Model | Test Accuracy | F1-Score (Macro) |
| :--- | :---: | :---: |
| Baseline | 61.26% | 0.6032 |
| Dropout-Only | 55.30% | 0.5376 |
| BatchNorm-Only | 56.62% | 0.5590 |
| L2-Only | 60.93% | 0.6031 |
| **Augmented Data** | **TBD** | **TBD** |

## Visualizations

### 1. Training Convergence (LAF Curves)
![Training GIF](./assets/training_process.gif)
*Animation showing the Loss and Accuracy evolution across epochs.*

### 2. Confusion Matrix
![Confusion Matrix](./assets/confusion_matrix.png)
*Detailed breakdown of emotion classification accuracy.*

## Installation
```bash
git clone https://github.com/username/SER.git
cd SER
pip install -r requirements.txt
```

## Usage
1. Open `ser-dpl.ipynb` in Jupyter or Colab.
2. Update dataset paths if necessary.
3. Run all cells to replicate the results and visualizations.
