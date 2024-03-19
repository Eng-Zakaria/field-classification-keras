# Text Classification with TensorFlow

This repository contains code for a text classification project using TensorFlow and scikit-learn. The project focuses on training a neural network model to classify text data into multiple categories.

## Overview

In this project, we leverage TensorFlow's Keras API for building and training a neural network model. The model architecture consists of an input layer and a single dense layer with a sigmoid activation function, suitable for binary classification tasks. We utilize scikit-learn for data preprocessing and evaluation of the model's performance.

## Key Features

- **TensorFlow Model Training:** Train a neural network model using TensorFlow's Sequential API.
- **Evaluation:** Compute training accuracy and make predictions on test data.
- **Data Preprocessing:** Convert sparse feature matrices to dense matrices before model training.
- **Customization:** Modify model architecture and parameters to suit specific classification tasks.

## Usage

1. **Clone the repository:**

```bash
git clone https://github.com/eng-zakaria/text-classification.git
cd text-classification
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Run the script:**

```bash
python text_classification.py
```

4. **Customization:**

Feel free to modify the script to suit your dataset and classification task.

## Requirements

- Python 3.x
- TensorFlow
- scikit-learn

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
