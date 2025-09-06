# Handwritten Digit Recognition Neural Network
A simple Neural Network that uses TensorFlow and Keras that recognizes handwritten digits form the MNIST dataset

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)](https://keras.io/)


---

## Features
- Loads & processes the MNIST dataset
- Builds a fully connected feedforward NN with:
  - 784 input neurons (28x28 image flattened)
  - 128 hidden neurons
  - 64 hidden neurons
  - 10 output neurons
- Trains with Adam optimizer & backpropagation
- Visualizes preidctions

---

## Quick Start
```bash
# Clone the repo
git clone https://github.com/yourusername/handwritten-digit-nn.git
cd handwritten-digit-nn

# Create/Activate VE
python -m venv .venv
.venv\Scripts\activate

# Install dependencies
pip install -U tensorflow numpy matplotlib jupyter

# Launch Jupyter Notebook
jupyter notebook

```

---

## Dataset
- MNIST dataset (60,000 training images + 10,000 testing images)
- 28x28 grayscale

---

## Training Results
```matlab
Epoch 1 -> 99.36%
Epoch 2 -> 99.58%
Epoch 3 -> 99.63%
Epoch 4 -> 99.53%
Epoch 5 -> 99.69%
```
## Test Accuracy
✅ 97.91% Accuracy on 10,000 images

---


## Credit
This project was inspired by the following tutorial:

[![YouTube Video](https://img.youtube.com/vi/VPlFpvLOgtQ/0.jpg)](https://www.youtube.com/watch?v=VPlFpvLOgtQ)
