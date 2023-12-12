
# Environment Setup

In order to ensure the successful execution of the code within this repository, it is imperative that certain prerequisites are met. Below is a detailed guide on the necessary steps to prepare your environment.

## Prerequisites

Before proceeding, please ensure that your system meets the following requirements:

- **Python**: This codebase is developed in Python. Make sure you have Python installed on your system. If not, you can download it from [Python's official website](https://www.python.org/downloads/).

## Required Packages

The following Python packages are essential for running the code:

1. **PyTorch**: A powerful library for deep learning. You can install it by following the instructions on the [official PyTorch website](https://pytorch.org/get-started/locally/).

2. **Torch Geometric**: An extension library for PyTorch specializing in graph neural networks. For installation, refer to the [Torch Geometric documentation](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html).

3. **Matplotlib**: A widely-used library for creating static, animated, and interactive visualizations in Python. Install it using pip with the command: `pip install matplotlib`.

## Installation Guide

To install the aforementioned packages, please execute the following commands in your terminal or command prompt:

```bash
pip install torch
pip install torch_geometric
pip install matplotlib
```

Ensure that each package is installed successfully before proceeding. If you encounter any issues during installation, please refer to the respective package's documentation for troubleshooting guidelines.

## Running .ipynb Files

To run `.ipynb` (Jupyter Notebook) files, you will need Jupyter Notebook or JupyterLab installed on your system. You can install these using pip:

```bash
pip install notebook
# or
pip install jupyterlab
```

Once installed, you can start Jupyter Notebook or JupyterLab using:

```bash
jupyter notebook
# or
jupyter lab
```

This will open a new browser window or tab displaying the Jupyter interface. From here, you can navigate to the `.ipynb` file you wish to run and open it.

Before running the notebook, make sure all necessary data files and dependencies are downloaded. If the notebook requires specific datasets or files, download them to the notebook's working directory or to the specified path within the notebook.

Finally, you can run the notebook cells sequentially by clicking on each cell and pressing `Shift + Enter`, or you can run all cells at once using the appropriate command in the Jupyter interface.
