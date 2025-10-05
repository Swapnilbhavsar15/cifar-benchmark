# PyTorch CIFAR-10 Benchmark

A simple, clean, and reproducible project to train and evaluate a Convolutional Neural Network (CNN) on the CIFAR-10 dataset using PyTorch.

This project is designed as a standard benchmark for evaluating the performance, reliability, and user experience of machine learning platforms and GPU infrastructure.

## Project Structure

- `model.py`: Defines the simple CNN architecture.
- `train.py`: Handles the data loading, training loop, and saves the trained model.
- `test.py`: Loads the trained model and evaluates its accuracy on the test set.
- `requirements.txt`: Lists the necessary Python packages.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd cifar-benchmark
    ```

2.  **Install dependencies:**
    It's recommended to use a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

## Usage

### 1. Training the Model

Run the training script from the terminal. You can adjust hyperparameters like epochs, learning rate, and batch size.

```bash
python train.py --epochs 10 --lr 0.001 --batch_size 64
