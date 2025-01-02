# Brain Tumor Classification and Segmentation

This project focuses on **brain tumor classification and segmentation** using deep learning techniques. It utilizes pre-operative multimodal MRI scans to identify and segment tumors, incorporating models like **CNN**, **ResNet**, and a modified **U-Net** architecture.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Model Architectures](#model-architectures)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [References](#references)

---

## Introduction

Brain tumors are a severe medical condition requiring accurate detection and segmentation. This project aims to classify and segment brain tumors from MRI scans using deep learning approaches. The implementation integrates **Few-Shot Learning** to handle limited data scenarios effectively.

---

## Dataset

- **Input**: Pre-operative multimodal MRI scans.
- **Formats Supported**: NIfTI (.nii), PNG, and JPEG.
- **Processing Tools**: `nilearn` and `nibabel` for loading and visualization.

---

## Model Architectures

1. **CNN** - For initial tumor classification.
2. **ResNet** - Pre-trained deep learning model for feature extraction.
3. **U-Net (Modified)** - Enhanced segmentation model tailored for medical imaging tasks.

---

## Installation

### Prerequisites

- Python 3.8 or later
- TensorFlow 2.x
- Keras
- Additional Libraries:
  ```bash
  pip install numpy pandas seaborn matplotlib scikit-image nilearn nibabel
  ```

### Clone Repository

```bash
git clone https://github.com/username/brain-tumor-classification.git
cd brain-tumor-classification
```

---

## Usage

### 1. Data Preparation

- Place MRI images in the `data/` folder.
- Organize images into `train/`, `test/`, and `validation/` subfolders.

### 2. Run Notebook

Execute the provided Jupyter notebook:

```bash
jupyter notebook Brain_Tumour_Classification.ipynb
```

### 3. Model Training

- Modify hyperparameters in the notebook as required.
- Monitor training using accuracy and loss plots.

---

## Results

- Achieves **high accuracy and segmentation performance** on benchmark datasets.
- Provides visualizations of tumor regions detected and segmented.

---

## References

- [Kaggle Brain MRI Dataset](https://www.kaggle.com/datasets)
- Research Papers on CNN, ResNet, and U-Net Architectures.
- Official TensorFlow and Keras Documentation.

