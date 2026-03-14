# LSTM from Scratch: Numerical Example Implementation

**Course Project:** AI424 - Deep Learning  
**Academic Year:** 2025/2026  
**Institution:** Faculty of Artificial Intelligence  

## 📌 Overview
This repository contains a Python implementation of the manual LSTM numerical example provided in the course material. The code demonstrates a step-by-step forward pass of an LSTM cell using predefined arbitrary weights.

## 🎯 Problem Statement
Given a sequential input $X = [1, 2, 3]$ and an evaluation at $t=4$, the objective is to manually compute the values for the Forget gate, Input gate, Candidate cell state, Cell state update, Output gate, and Hidden state at each time step. A final linear transformation ($\hat{y} = W_y h_t + b_y$) is applied to predict the next numerical value in the sequence.

## ⚙️ Implementation Details
- **Language:** Python
- **Dependencies:** Standard `math` library (No external ML frameworks).
- **Process:** Iterates through 4 time steps, calculating gate activations using Sigmoid and Tanh functions, updating the hidden ($h_t$) and cell states ($C_t$), and concluding with a final scalar prediction matching the exact mathematical outputs of the assigned PDF (Predicting ~3.8).
