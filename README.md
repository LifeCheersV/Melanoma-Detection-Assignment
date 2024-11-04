# Melanoma Detection using CNN

This project develops a Convolutional Neural Network (CNN) model to detect melanoma from skin images. Melanoma is a dangerous type of skin cancer responsible for most skin cancer fatalities. This tool aims to assist dermatologists by providing early detection, which could lead to improved outcomes for patients.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Requirements](#requirements)
5. [Usage](#usage)
6. [Model Architecture](#model-architecture)
7. [Results](#results)

---

### Overview

This CNN-based project automates the identification of melanoma from skin images. Early detection through such tools can reduce diagnostic effort and potentially save lives.

### Dataset

The dataset consists of labeled skin images and includes:
- **Images**: Visual samples for training and testing the CNN model.
- **Labels**: Indicating the presence or absence of melanoma.

### Project Structure

- **Cancer_Detection_Assignment.ipynb**: The main notebook file, containing data loading, preprocessing, model building, and evaluation steps.

### Requirements

This project requires the following libraries:
- Python 3.x
- Jupyter Notebook
- `tensorflow`
- `pandas`
- `numpy`
- `matplotlib`
- `PIL` (for image processing)

To install dependencies:
```bash
pip install -r requirements.txt
```

### Usage
#### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/melanoma-detection.git
cd melanoma-detection
```
#### 2. Run the notebook:

```bash
jupyter notebook Cancer_Detection_Assignment.ipynb
```
#### 3. Follow the instructions in the notebook for running each cell, especially data loading from Google Drive if applicable.
### Model Architecture
The CNN model is designed to process images and detect melanoma disease. It includes layers for convolution, pooling, and fully connected layers optimized for binary classification (melanoma or non-melanoma).

### Results:

The final section of the notebook provides:
1) Accuracy and Loss Graphs: Model performance visualization.
2) Evaluation Metrics: Precision, recall, F1-score, and accuracy of the CNN.