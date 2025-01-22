# CPU vs GPU Training Time Comparison with TensorFlow

This project demonstrates a comparison of training times for a ResNet50 model on the CIFAR-10 dataset using TensorFlow, running on both CPU and GPU. 

---

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Setup and Requirements](#setup-and-requirements)
- [Running the Code](#running-the-code)


---

## Overview

This demo is part of a learning module designed to provide hands-on experience in comparing computational performance on different hardware setups. Specifically, the goals are to:
- Train a ResNet50 model on the CIFAR-10 dataset.
- Compare the training times on a CPU and a GPU.
- Visualize the training time difference using a bar chart.
- Gain practical insights into optimizing machine learning workflows for various hardware configurations, a critical aspect of modern AI and ML development.


---

## Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow
- **Architecture**: ResNet50
- **Visualization**: Matplotlib
- **Dataset**: CIFAR-10
- **Hardware**: NVIDIA GPU (CUDA-enabled)

---

## Setup and Requirements

### Prerequisites
- Python 3.8 or later
- TensorFlow 2.0 or later
- Matplotlib
- NVIDIA GPU with CUDA support (if using a GPU)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```
    cd hpc
    ```

3. Install required Python libraries:
    ```
    pip install 'tensorflow[and-cuda]' matplotlib
    ```

---
## Running the Code
1. Check GPU availability:
    ```
    !nvidia-smi
    ```

2. Execute the Python script:

    ```
    python train_resnet_comparison.py
    ```
3. The script will:
- Train the ResNet-like model on the CIFAR-10 dataset using both CPU and GPU.
- Record the training time for each device.
- Display a bar chart comparing the training times.

---
### End Note

Thank you for your interest in this demo! We welcome any feedback. Feel free to reach out to us.