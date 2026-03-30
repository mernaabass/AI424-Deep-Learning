# 🚗 Driver Drowsiness Detection using Hybrid CNN-LSTM Model

[![Accuracy](https://img.shields.io/badge/Test%20Accuracy-99.23%25-brightgreen.svg)](https://github.com/mernaabass/AI424-Deep-Learning/Driver-Drowsiness-Detection-CNN-LSTM)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-orange.svg)](https://pytorch.org/)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)

**Hybrid CNN-LSTM model built from scratch achieving 99.23% accuracy on Driver Drowsiness Dataset (DDD). Perfect for road safety applications.**

## 🎯 **Project Overview**
Detects driver drowsiness from facial image sequences using:
- **CNN (4 layers)**: Spatial feature extraction (eyes, head pose)
- **LSTM (2 bidirectional layers)**: Temporal analysis (blink patterns)
- **Final Accuracy**: **99.23%** on 1,045 test sequences

## 📊 **Performance Highlights**
| Metric          | Value    |
|-----------------|----------|
| **Test Accuracy** | **99.23%** |
| **Precision (Drowsy)** | 99% |
| **Recall (Drowsy)**   | 100% |
| **F1-Score**         | 99% |

## 🛠️ **Tech Stack**
🔥 PyTorch 2.0+
📊 Driver Drowsiness Dataset (DDD) - 41,793 images
💻 Kaggle GPU P100
## 🎓 **Model Architecture**
Input: [batch, 3, 16, 224, 224]
↓
CNN (4 Layers + MaxPooling)
↓ [batch, 16, 256]
LSTM (2 Bidirectional Layers)
↓ [batch, 256]
Fully Connected Classifier
↓ Drowsy / Non-Drowsy (99.23% acc)
## 🏆 **Why This Model Rocks**
- ✅ **From scratch** (no pre-trained weights)
- ✅ **State-of-the-art accuracy** (99.23%)
- ✅ **Real-world application** (driver safety)
