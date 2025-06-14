# 🧠 Breast Cancer Detection using Neural Network

This project demonstrates how to build a neural network model using TensorFlow/Keras to detect breast cancer based on features in the [Scikit-learn Breast Cancer dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html).

---

## 📊 Problem Statement

- **Goal**: Predict whether a tumor is **malignant (1)** or **benign (0)**.
- **Dataset**: Comes from `sklearn.datasets.load_breast_cancer()`.
- **Features**: 30 numeric features computed from digitized images of fine needle aspirate (FNA) of a breast mass.

---

## 🏗️ Model Architecture

- Input Layer: 30 neurons (one for each feature)
- Hidden Layers: Dense layers with ReLU activations
- Dropout layer for regularization
- Output Layer: 1 neuron with sigmoid activation

### 🔧 Compile Settings

- **Loss Function**: `binary_crossentropy`
- **Optimizer**: `adam`
- **Metrics**: `accuracy`

---

## ✅ Accuracy Achieved

- **Training Accuracy**: ~97–98%
- **Validation Accuracy**: ~95–97%
- Final accuracy may vary slightly based on random seed and dropout.

---

## 📁 Files Included

| File                             | Description                                 |
|----------------------------------|---------------------------------------------|
| `breast_cancer_detection.ipynb` | Jupyter Notebook with all code and plots    |
| `breast_cancer_model.h5`        | Saved trained model in Keras HDF5 format    |
| `requirements.txt`              | List of Python libraries to install         |

---

## ▶️ How to Run

1. Clone the repo: git clone https://github.com/neural_network_models/breast-cancer-detection.git
cd breast-cancer-detection
