# Practical Deep Learning for Coders

A hands-on exploration of deep learning concepts following the [Fast.ai course](https://course.fast.ai) and accompanying book. This repository demonstrates practical image classification using fastai and PyTorch with different ResNet architectures.

## What This Project Does

- **Image Classification**: Train models to recognize different categories (pets, landscapes, objects)
- **Model Comparison**: Compare ResNet18, ResNet50, and ResNet152 architectures
- **Interactive Testing**: Upload images to test trained models in real-time
- **Hardware Optimization**: Leverages Apple Silicon (MPS), CUDA, or CPU depending on availability

## Notebooks

- **`01_intro.ipynb`** - Main introduction with custom image classification and model comparison
- **`01_intro-resnet18.ipynb`** - Pet breed classification using ResNet18
- **`01_intro-resnet50.ipynb`** - Pet breed classification using ResNet50
- **`01_intro-resnet152.ipynb`** - Pet breed classification using ResNet152

## Features

- **Multi-category image classification** (cats, dogs, forests, mountains, cities)
- **Pet breed recognition** with 37 different breeds
- **Interactive image upload** for real-time testing
- **Model architecture comparison** across ResNet variants
- **Hardware optimization** for Apple Silicon (MPS), CUDA, or CPU

## Prerequisites

- **Python**: 3.13.5 (managed via pyenv)
- **Operating System**: macOS (optimized for Apple Silicon) or Linux (for CUDA support)
- **Hardware**:
  - Apple Silicon Mac (for MPS acceleration)
  - NVIDIA GPU (for CUDA acceleration)
  - CPU-only systems supported

## Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd deep-learning-for-coders
   ```

2. **Set up Python environment** (using pyenv):

   ```bash
   pyenv install
   ```

3. **Create and activate virtual environment**:

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On macOS/Linux
   ```

4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Quick Start

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Start with the main notebook**:
   Open `01_intro.ipynb` for a comprehensive introduction to the project

3. **For specific model experiments**:
   - `01_intro-resnet18.ipynb` - Fast training with ResNet18
   - `01_intro-resnet50.ipynb` - Balanced performance with ResNet50
   - `01_intro-resnet152.ipynb` - Maximum accuracy with ResNet152

## Resources

- [Fast.ai Course](https://course.fast.ai) - Free deep learning course
- [Fast.ai Book](https://github.com/fastai/fastbook) - Comprehensive deep learning book

## License

This project is for educational purposes. Please respect the licenses of the datasets and libraries used.
