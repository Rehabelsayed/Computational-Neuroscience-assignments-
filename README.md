# Computational Neuroscience Assignments – RNN from Scratch

This repository contains an assignment for **Computational Neuroscience**, where we were required to implement a **Recurrent Neural Network (RNN)** from scratch using only **NumPy**.

## Assignment Objective

> Build your own RNN for any text you choose. The text contains 4 words. The target is predicting the 4th word.

### Example Used:
**Input**: "MAKE", "WHAT", "YOU"  
**Target**: "WANT"

The model learns to predict the word "WANT" after seeing the previous 3 words.

## Key Features

- Implemented RNN manually (no ML libraries used)
- One-hot encoded inputs
- Feedforward with tanh activation
- Softmax output for word prediction
- Backpropagation Through Time (BPTT)
- Cross-entropy loss function
- Gradient descent-based weight updates

## File Description

- `RNN_MODEL.ipynb`: The main notebook that contains all code for building, training, and testing the RNN model

## Technologies

- Python 3.x
- NumPy
- Jupyter Notebook

## Output Sample

```
Epoch 0, Loss: 1.3871, Prediction: WHAT
...
Epoch 2000, Loss: 0.0025, Prediction: WANT

Final Prediction: WANT
```

## Author

Prepared by [Rehab Elsayed ] as part of the **Computational Neuroscience** course assignment.

Supervised by **A. Prof. Noha El-Attar**

---

