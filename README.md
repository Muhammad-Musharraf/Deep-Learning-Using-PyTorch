# 🔥 Deep Learning Using PyTorch

> A comprehensive collection of deep learning projects, models, and tutorials implemented with PyTorch — covering neural networks, model training, evaluation, and practical AI applications.

[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

---

## 📚 Table of Contents

- [About](#-about)
- [Repository Structure](#-repository-structure)
- [Topics Covered](#-topics-covered)
- [Getting Started](#-getting-started)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [License](#-license)
- [Author](#-author)

---

## 🧠 About

This repository serves as a hands-on learning resource for **Deep Learning with PyTorch**. It covers core concepts from the ground up — starting with PyTorch fundamentals — and progressively advances into building, training, and evaluating real-world neural network architectures including ANNs, CNNs, RNNs, and LSTMs. Transfer learning and hyperparameter optimization with Optuna are also included.

All implementations are written in **Jupyter Notebooks** for an interactive, educational experience.

---

## 📁 Repository Structure

```
Deep-Learning-Using-PyTorch/
│
├── 📂 PyTorch Fundamental/          # Core PyTorch concepts: tensors, autograd, ops
├── 📂 PyTorch Notes/                # Summary notes and key concepts for reference
├── 📂 Dataset & DataLoader Class/   # Custom datasets and efficient data pipelines
├── 📂 Artificial Neural Network (ANN)/   # Fully connected feedforward networks
├── 📂 Convolutional Neural Network (CNN)/ # Image classification with CNNs
├── 📂 Recurrent Neural Network (RNN)/    # Sequential data modeling with RNNs
├── 📂 LSTM/                         # Long Short-Term Memory networks
├── 📂 Transfer Learning/            # Fine-tuning pretrained models
├── 📂 Optuna Basic/                 # Hyperparameter tuning with Optuna
│
├── LICENSE
└── README.md
```

---

## 🗂️ Topics Covered

| Module | Description |
|---|---|
| **PyTorch Fundamentals** | Tensors, operations, autograd, device management (CPU/GPU) |
| **PyTorch Notes** | Quick-reference notes and concept summaries |
| **Dataset & DataLoader** | Building custom datasets, batching, shuffling, and data pipelines |
| **Artificial Neural Network (ANN)** | Feedforward networks for classification and regression tasks |
| **Convolutional Neural Network (CNN)** | Feature extraction and image recognition using conv layers |
| **Recurrent Neural Network (RNN)** | Sequence modeling for time-series and text data |
| **LSTM** | Long-term dependency learning with LSTM cells |
| **Transfer Learning** | Leveraging pretrained models (e.g. ResNet, VGG) for new tasks |
| **Optuna Basic** | Automated hyperparameter optimization using Optuna framework |

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- PyTorch (with or without CUDA)
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Muhammad-Musharraf/Deep-Learning-Using-PyTorch.git
cd Deep-Learning-Using-PyTorch
```

2. **Create and activate a virtual environment** *(recommended)*

```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```

3. **Install required packages**

```bash
pip install torch torchvision torchaudio
pip install jupyter notebook optuna matplotlib numpy scikit-learn
```

> 💡 For GPU support, visit the [official PyTorch installation page](https://pytorch.org/get-started/locally/) and select your CUDA version.

---

## 💻 Usage

Launch Jupyter Notebook and open any `.ipynb` file to start exploring:

```bash
jupyter notebook
```

Navigate into any module folder (e.g., `Convolutional Neural Network (CNN)/`) and open the notebook to run cells interactively.

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0**.
See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Muhammad Musharraf**

- GitHub: [@Muhammad-Musharraf](https://github.com/Muhammad-Musharraf)

---

> ⭐ If you find this repository helpful, please consider giving it a star — it motivates further development!
