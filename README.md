# Facial-Detection-KNN-SVM-GaussianNB
This project implements facial recognition using custom KNN, SVM, and Gaussian NB. It features a tailored KNN for optimized facial analysis, SVM for complex feature differentiation, and Gaussian NB for statistical predictions. 
## Dataset
The dataset used in this project consists of facial images represented in a tabular format. Each row corresponds to a facial image, and each column represents a pixel value or feature.

## Usage

1. Load the dataset using Pandas.
2. Pre-process the dataset by normalizing each face image vector to unit length. This normalization step ensures that each image vector has a magnitude of 1, which is essential for the facial recognition process.
3. Apply machine learning techniques to train a model for recognizing faces from the dataset.

## Code Structure

- **Data Loading**: The dataset is loaded into a DataFrame.
- **Pre-processing**: Normalization of the facial image vectors to unit length.
- **Labeling**: Assign labels to the dataset for supervised learning.
- **Model Training**: (Details on model training can be added based on further cells in the notebook).

## License
This project is licensed under the [MIT License](https://opensource.org/license/MIT)- see the LICENSE file for details.
