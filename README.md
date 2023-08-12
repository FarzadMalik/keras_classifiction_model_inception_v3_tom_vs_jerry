![image](https://github.com/FarzadMalik/keras_classifiction_model_inception_v3_tom_vs_jerry/assets/107833662/2e9ba1aa-fc40-43eb-9763-5611856f1ec7)

# Tom vs Jerry Image Classification

This repository contains code for building and training a deep learning model to classify images of "Tom and Jerry" characters using TensorFlow and Keras.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to classify images of "Tom and Jerry" characters into four classes: Tom, Jerry, None (neither Tom nor Jerry), and Both (both characters together). The model architecture is based on the InceptionV3 CNN architecture, and the training process includes data preprocessing, model compilation, training with callbacks, and early stopping.

## Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/tom-vs-jerry-image-classification.git
cd tom-vs-jerry-image-classification
```

2. Set up a virtual environment (optional but recommended):

```bash
python3 -m venv venv
source venv/bin/activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Prepare your dataset of "Tom and Jerry" images and organize them in the `images/train` directory.

2. Modify the `classification_model.ipynb` notebook to match your dataset and project requirements.

3. Run the notebook to train the model and generate predictions.

## Project Structure

The repository is organized as follows:

```
tom-vs-jerry-image-classification/
│
├── images/
│   ├── train/                         # Training image dataset
│   │   ├── jerry/
│   │   ├── tom/
│   │   ├── tom_jerry_0/
│   │   └── ...                         # Other image directories
│   └── ...                            # Other image directories (if applicable)
│
├── classification_model.ipynb         # Jupyter Notebook for training and predictions
├── tom_vs_jerry_1000_epochs.h5        # Saved model weights (after 1000 epochs)
├── tom_vs_jerry_100_epochs.h5         # Saved model weights (after 100 epochs)
├── tom_vs_jerry_Checkpoint.h5         # Best model weights (with callbacks)
├── requirements.txt                   # List of required packages
├── file_structure.txt                 # File containing the project file structure
└── README.md                          # Project documentation
```

## Results

You can find the trained model weights and performance plots in the repository. The `tom_vs_jerry_1000_epochs.h5` file contains the saved weights after training for 1000 epochs. The `classification_model.ipynb` notebook provides step-by-step instructions for training the model and generating predictions.

<img width="515" alt="image" src="https://github.com/FarzadMalik/keras_classifiction_model_inception_v3_tom_vs_jerry/assets/107833662/9b7710fb-8fd1-430d-8039-811cddccf700">

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

