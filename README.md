# README

## Project Overview

This project demonstrates the implementation of a convolutional neural network (CNN) using TensorFlow and Keras to classify images from the Fashion MNIST dataset. The dataset includes 10 categories of clothing items, such as T-shirts, trousers, dresses, and more.

## Project Structure

- **Model Training and Saving**: The `train_and_save_model` function handles loading the Fashion MNIST dataset, training the CNN model, and saving it to a file (`fashion_mnist_model.h5`).
- **Model Loading**: The `load_model` function is used to load the pre-trained model from the file.
- **Image Prediction**: The `predict_image` function takes an image as input and returns the model's prediction.

## Dependencies

- TensorFlow
- NumPy
- Matplotlib

Install the required packages using:
```bash
pip install tensorflow numpy matplotlib
```

## Usage

1. **Train and Save the Model:**
   Run the `train_and_save_model` function to train the CNN model on the Fashion MNIST dataset and save it locally.

2. **Load the Model:**
   Use the `load_model` function to load the saved model for predictions.

3. **Make Predictions:**
   Use the `predict_image` function to classify an image. The function returns predictions for the input image, indicating the likelihood of each class.

## Example Output

After training, the model will display the test accuracy. Example output:
```
Dokładność na danych testowych: 0.91
```

## License

This project is open-source and available under the MIT License.
