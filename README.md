# Vision Transformer (ViT) Model

This repository contains a Jupyter notebook (`VITmodel.ipynb`) for experimenting with Vision Transformer (ViT) models using PyTorch and torchvision. The notebook is designed for running on GPU-enabled environments and demonstrates the setup for deep learning experiments with image data.

## Features
- GPU support detection and configuration
- PyTorch and torchvision integration
- Data loading and transformation utilities
- Ready for further development of Vision Transformer architectures

## Requirements
- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib

You can install the required dependencies using pip:

```bash
pip install torch torchvision numpy matplotlib
```

## Usage
1. Open `VITmodel.ipynb` in Jupyter Notebook or Google Colab.
2. The notebook will automatically detect if a CUDA-enabled GPU is available and use it for computations.
3. The initial cells set up the environment and import necessary libraries. You can extend the notebook to implement and train Vision Transformer models on your dataset.

## GPU Support
The notebook checks for GPU availability and sets the device accordingly. It also includes a cell to display GPU information using `nvidia-smi` (works in Colab and compatible environments).

## License
This project is licensed under the terms of the LICENSE file in this repository. 