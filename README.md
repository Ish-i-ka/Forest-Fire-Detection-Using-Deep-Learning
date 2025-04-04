# Forest-Fire-Detection-Using-Deep-Learning

This script prepares the environment and data for a Forest Fire Detection Model using TensorFlow.

## Description

The script performs the following actions:

1.  **Imports necessary libraries:** Includes `os`, `numpy`, `matplotlib`, and `tensorflow`.
2.  **Dataset Handling:** Attempts to download the "the-wildfire-dataset" from Kaggle Hub or uses a predefined path if the download fails or the dataset is already available locally.
3.  **Directory Setup:** Defines paths for the training, validation, and testing datasets based on the dataset's structure.
4.  **GPU Check:** Verifies the availability of a GPU for TensorFlow acceleration.
5.  **Class Identification:** Determines the classes present in the training data (expected: 'fire', 'no_fire').
6.  **Sample Counting:** Counts the number of images within each class for the training, validation, and test sets.
7.  **Data Visualization:** Displays sample images from each class in the training set using Matplotlib to provide a visual overview.

## Dependencies

*   Python 3.x
*   TensorFlow
*   NumPy
*   Matplotlib
*   kagglehub (optional, for downloading the dataset directly)

## Dataset 

This script uses "The Wildfire Dataset" (specifically `the_wildfire_dataset_2n_version`). Ensure the dataset is available at the specified path or can be downloaded via `kagglehub`.
