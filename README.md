# Flower Classification with CNN and Keras Tuner

This notebook shows how to build a Convolutional Neural Network (CNN) for flower classification using TensorFlow and Keras Tuner. It uses the `tf_flowers` dataset, which contains images of five different flower types: dandelion, daisy, tulips, sunflowers, and roses.


## Notebook Structure

The notebook is organized into the following sections:

1. **Finding the dataset:** Loads the `tf_flowers` dataset using TensorFlow Datasets and displays some sample images.
2. **Initial data processing:** Preprocesses the images by resizing and normalizing them. Splits the data into training, validation, and test sets.
3. **Writing a simple convolutional network without a tuner:** Builds a basic CNN model and trains it on the training data. Evaluates the model's performance on the test set.
4. **Finding CNN using tuner:** Uses Keras Tuner to find the optimal hyperparameters for the CNN model. This involves defining a search space for the hyperparameters and using a Bayesian Optimization algorithm to explore the search space.
5. **TensorBoard:** Visualizes the training process and hyperparameter tuning results using TensorBoard.

## Requirements

- Python 3.7 or higher
- TensorFlow
- TensorFlow Datasets
- Keras Tuner
- Matplotlib
- NumPy

## How to Run

1. Make sure you have all the required libraries installed. You can install them using `pip`:
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the cells in the notebook cell by cell.
4. To view the TensorBoard visualizations, you need to replace /content/tf_flowers/bayesian_opt20241210-195027 with your actual path:

## My Tensorboard plots for accuracy and loss (for 10 different Hyperband trials with training and validation).
1. Accuracy

![acc](https://github.com/user-attachments/assets/4dc3bec1-1ce7-4848-a0ba-72d1b710b684)

2. Loss

![loss](https://github.com/user-attachments/assets/45dc3764-4446-46b0-bffc-7287df15a5d1)
