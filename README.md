# Keras ResNet-50 Transfer Learning for Flower Classification

![Flowers](![image](https://github.com/sumantkale/Keras_Resnet_50_Transfer_learning_Flowers/assets/129871706/d7cb9159-878f-402e-872f-dcb9b7338272)
)

## Overview

This project demonstrates the use of transfer learning with the ResNet-50 architecture in Keras to classify images of three different types of flowers: rose, daisy, and dandelion. Transfer learning allows us to leverage a pre-trained neural network to solve a similar problem efficiently.

## Dataset

We used the [Flowers Recognition dataset], which contains labeled images of flowers in various categories. In this project, we focused on three classes: rose, daisy, and dandelion. The dataset is divided into training and validation sets.

## Prerequisites

- Python 3.x
- Keras
- TensorFlow
- NumPy
- Matplotlib

You can install the required packages using `pip`:

```bash
pip install keras tensorflow numpy matplotlib
```

## Project Structure

The project is organized as follows:

- `data/`: This directory contains the dataset. You should place the dataset images here.
- `train.py`: The script to train the ResNet-50 model on the dataset.
- `predict.py`: A script to make predictions on new images using the trained model.
- `model/`: This directory stores the saved model weights and architecture.
- `utils/`: Utility functions for data preprocessing and visualization.

## Usage

1. **Data Preparation**: Download the dataset and place the images in the `data/` directory.

2. **Training**: Train the ResNet-50 model on the dataset using the following command:

   ```bash
   python train.py
   ```

   The trained model will be saved in the `model/` directory.

3. **Prediction**: You can make predictions on new images using the trained model with the following command:

   ```bash
   python predict.py path/to/image.jpg
   ```

   Replace `path/to/image.jpg` with the path to the image you want to classify.

## Results

After training, you can view the training and validation accuracy and loss curves in the generated plots. Additionally, you can evaluate the model's performance on the test dataset using various metrics such as accuracy, precision, recall, and F1-score.


## Acknowledgments

- The ResNet-50 model is based on the Keras Applications library.

## Contact

If you have any questions or suggestions, please feel free to contact us at [sumantkale1999@gmail.com](mailto:sumantkale1999@gmail.com).

