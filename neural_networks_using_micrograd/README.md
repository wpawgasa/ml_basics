# ML_Basics

A comprehensive collection of machine learning implementations and examples covering fundamental algorithms and techniques in pattern recognition and probabilistic machine learning.

## 📁 Repository Structure

```
ML_Basics/
├── notebooks/                     # Jupyter notebooks with ML implementations
│   ├── Bayesian_Neural_Network.ipynb
│   ├── DecisionTree_vs_RandomForest.ipynb
│   ├── Gaussian_Process_Inference_Example.ipynb
│   ├── Gaussian_Process_Prior.ipynb
│   ├── Kernel_functions.ipynb
│   ├── Kernel_Ridge_Regression.ipynb
│   ├── Probabilistic_BNN.ipynb
│   ├── RBF_Networks.ipynb
│   ├── RVM.ipynb
│   └── SVM.ipynb
├── libs/
│   └── PRML/                      # Pattern Recognition and Machine Learning implementations
├── neural_networks_using_micrograd/  # Neural network implementations with micrograd
└── .devcontainer/                 # Development container configuration
```

## 🚀 Getting Started

This repository is configured to work with VS Code Dev Containers, providing a consistent development environment with all necessary dependencies pre-installed.

### Prerequisites
- Docker
- VS Code with Dev Containers extension

### Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ML_Basics
   ```

2. Install project dependencies from `pyproject.toml`

## 📚 Notebooks Overview

### Bayesian Methods
- **[Bayesian_Neural_Network.ipynb](notebooks/Bayesian_Neural_Network.ipynb)**: Implementation of Bayesian Neural Networks using TensorFlow Probability, demonstrating uncertainty quantification in deep learning
- **[Probabilistic_BNN.ipynb](notebooks/Probabilistic_BNN.ipynb)**: Extended probabilistic approaches to neural networks

### Gaussian Processes
- **[Gaussian_Process_Prior.ipynb](notebooks/Gaussian_Process_Prior.ipynb)**: Understanding GP priors and their properties
- **[Gaussian_Process_Inference_Example.ipynb](notebooks/Gaussian_Process_Inference_Example.ipynb)**: Practical GP inference examples

### Kernel Methods
- **[Kernel_functions.ipynb](notebooks/Kernel_functions.ipynb)**: Exploration of different kernel functions in scikit-learn, including linear, RBF, and polynomial kernels with SVM classification
- **[Kernel_Ridge_Regression.ipynb](notebooks/Kernel_Ridge_Regression.ipynb)**: Comparison between Support Vector Regression (SVR) and Kernel Ridge Regression, including performance analysis and learning curves
- **[RVM.ipynb](notebooks/RVM.ipynb)**: Relevance Vector Machine implementation for both regression and classification tasks
- **[SVM.ipynb](notebooks/SVM.ipynb)**: Support Vector Machine implementations and examples

### Neural Networks
- **[RBF_Networks.ipynb](notebooks/RBF_Networks.ipynb)**: Radial Basis Function neural networks

### Tree-Based Methods
- **[DecisionTree_vs_RandomForest.ipynb](notebooks/DecisionTree_vs_RandomForest.ipynb)**: Comparative analysis of decision trees and random forests

## 🛠 Key Features

- **Comprehensive Coverage**: From basic kernel methods to advanced Bayesian neural networks
- **Practical Examples**: Real implementations with visualization and performance analysis
- **Educational Focus**: Clear explanations and step-by-step implementations
- **Modern Tools**: Uses TensorFlow Probability, scikit-learn, and other state-of-the-art libraries
- **Reproducible Environment**: Dev container ensures consistent setup across different machines

## 📖 Dependencies

The notebooks primarily use:
- **Python 3.12+**
- **TensorFlow & TensorFlow Probability** - For Bayesian neural networks
- **scikit-learn** - For classical ML algorithms
- **NumPy & Matplotlib** - For numerical computing and visualization
- **PRML library** - Custom implementations from Pattern Recognition and Machine Learning

## 📄 License

This project is open source. Please check individual files for specific licensing information.

## 🔗 References

Many implementations are inspired by or adapted from:
- Bishop, C. M. "Pattern Recognition and Machine Learning"