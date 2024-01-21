# Simple-MNIST-with-Adam-Optimizer-from-Scratch-
# Neural Network Classification Project

This project implements a simple neural network for image classification using Python and NumPy. The neural network is trained on a dataset and optimized using the Adam optimizer.

## Overview

The goal of this project is to build and train a neural network for image classification. The dataset used for training is stored in the "train.csv" file. The neural network consists of two layers: one hidden layer with ReLU activation and one output layer with softmax activation.

## Requirements

- Python 3.x
- NumPy
- pandas
- matplotlib

Install the required dependencies using the following command:

```bash
pip install numpy pandas matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/hjuvvana/Simple-MNIST-with-Adam-Optimizer-from-Scratch.git
cd Simple-MNIST-with-Adam-Optimizer-from-Scratch
```

2. Run the main script:

```bash
python neural_network_classification.py
```

3. Adjust hyperparameters:

Feel free to modify hyperparameters such as learning rate (`alpha`), number of iterations, etc., in the script to observe the impact on the training process.

## Structure

- `neural_network_classification.py`: Main script containing the neural network implementation.
- `train.csv`: Dataset for training the neural network.

## Results

The script will output the training accuracy at regular intervals during the training process. Additionally, it will display predictions and corresponding labels for a few training examples after training.

## License

This project is licensed under the [MIT License](LICENSE).
