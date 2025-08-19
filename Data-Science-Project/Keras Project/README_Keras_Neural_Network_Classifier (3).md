# Keras Neural Network Classifier

This project demonstrates how to build and train a neural network for binary classification using TensorFlow and Keras.

##  Objective

Train a deep learning model to classify structured data using:
- Fully connected neural network layers
- Dropout regularization
- Early stopping to prevent overfitting

##  Model Architecture

- Input layer normalized with `MinMaxScaler`
- Hidden layers with ReLU activation
- Dropout layer to mitigate overfitting
- Output layer with sigmoid activation for binary classification

## Dataset

- Synthetic classification dataset generated via `make_classification` from `sklearn.datasets`
- Features scaled between 0 and 1

##️ Libraries Used

- `TensorFlow` / `Keras`
- `NumPy`
- `Pandas`
- `Scikit-learn`
- `Matplotlib`

##  How to Run

1. Create a virtual environment (recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open `03-Keras-Project-Final-Rewrite.ipynb` and run all cells.

## results

- Achieved high classification accuracy with early stopping enabled
- Plotted training & validation loss to monitor overfitting
- Demonstrated good separation between predicted classes
