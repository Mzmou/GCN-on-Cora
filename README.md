
# Loading Libraries

This repository demonstrates the use of **Graph Neural Networks (GNNs)** for analyzing the **Cora dataset**. 
The implementation leverages PyTorch and PyTorch Geometric for graph-based deep learning.

## Description

The notebook provides a step-by-step guide to implementing a GNN model, specifically for training and evaluating on the Cora dataset. 
It includes data preprocessing, model building, training, and evaluation.

## Libraries Used

The following Python libraries are utilized in this project:

- `networkx`
- `matplotlib`
- `sklearn`
- `torch`
- `torch_geometric`

## Key Steps in the Notebook

1. **Library Loading:** Essential libraries for GNNs and dataset handling are imported.
2. **Data Preprocessing:** Prepares the Cora dataset for training.
3. **Model Implementation:** A GCN (Graph Convolutional Network) is defined using PyTorch Geometric's `GCNConv`.
4. **Training the Model:** Trains the GCN using labeled data from the dataset.
5. **Evaluation:** Assesses the model's performance on a test set.

## How to Run

To run this notebook on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/Mzmou/GCN-on-Cora.git
    cd GCN-on-Cora
    ```


2. Launch Jupyter Notebook and open `Training_GNN_using_Cora.ipynb`:
    ```bash
    jupyter notebook
    ```

3. Follow the steps in the notebook to train and evaluate the model.

## Requirements

Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook
- Required Python libraries (install via `pip install -r requirements.txt`)

## Dataset

The Cora dataset is used for this project. Ensure you have access to the dataset, either via PyTorch Geometric's dataset loader or by downloading it directly.

## Author

Feel free to reach out for collaboration or queries.

---
