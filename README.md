# ECE5831-Project
# Simple GAN Project on MNIST and California Housing Data

## Team Members
- HARSHA VARDHAN SAI MACHINENI
- Pooja Reddy Alumala
- Laasya Muddala

## Roles in the Project
- HARSHA VARDHAN SAI MACHINENI - [Data Analysis and Model Development]
- Pooja Reddy Alumala - [ Data Preprocessing and Visualization]
- Laasya Muddala - [Model Testing and Documentation]

## Project Summary
This project involves the application of a Simple Generative Adversarial Network (GAN) to two distinct datasets: the MNIST dataset of handwritten digits and the California Housing data. The project aims to explore the effectiveness of GANs in generating synthetic data that mimics the original datasets in terms of distribution and characteristics. The MNIST dataset serves as a benchmark for the GAN model, while the extension to the California Housing data demonstrates the model's adaptability to more complex, real-world datasets.

## Dataset Access Instructions

### MNIST Dataset
- **Description**: A large database of handwritten digits used for training image processing systems.
- **Access Instructions**:
  - Import TensorFlow and TensorFlow Datasets (TFDS).
  - Use TFDS to load the MNIST dataset.
  - Example Code:
    ```python
    import tensorflow as tf
    import tensorflow_datasets as tfds

    mnist_dataset = tfds.load('mnist', split='train', as_supervised=True)
    ```

### California Housing Dataset
- **Description**: Dataset with median house values from the 1990 California census.
- **Access Instructions**:
  - Similar to MNIST, import TensorFlow and TensorFlow Datasets.
  - Use TFDS to load the dataset.
  - Example Code:
    ```python
    import tensorflow as tf
    import tensorflow_datasets as tfds

    california_housing = tfds.load('california_housing', split='train', as_supervised=True)
    ```
