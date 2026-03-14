# LSTM from Scratch: Numerical Sequence Prediction

**Course Project:** AI424 - Deep Learning  
**Academic Year:** 2025/2026  
**Institution:** Faculty of Artificial Intelligence  
*Developed for the AI424 - Deep Learning course.*

## 📌 Overview
This repository contains a complete, from-scratch implementation of a Long Short-Term Memory (LSTM) neural network using only Python and `NumPy`. The objective of this assignment is to demonstrate a deep mathematical understanding of LSTM cells by implementing the forward pass, backpropagation through time (BPTT), and weight updates without relying on high-level deep learning frameworks like TensorFlow or PyTorch.

## 🎯 Problem Statement
The network is built and trained to recognize and learn from a simple numerical sequence. Given the input sequence vector `[1, 2, 3]`, the model is expected to learn the underlying pattern and accurately predict the next logical number, which is `[4]`.

## ⚙️ Implementation Details
- **Language:** Python
- **Dependencies:** `NumPy` (strictly for matrix and vector operations)
- **Network Architecture:** - Input Size: 1
  - Hidden State Size: 4 Cells
  - Output Size: 1
- **Gates Implemented:** - Forget Gate ($f_t$)
  - Input Gate ($i_t$)
  - Candidate Cell State ($\tilde{C}_t$)
  - Output Gate ($o_t$)

## 🚀 How to Run
The implementation is divided into logical cells for clarity. Simply run the Jupyter/Colab notebook sequentially. The model will initialize random weights, perform training over 2000 epochs, and output the loss and prediction progress until it converges close to the expected output (4).
