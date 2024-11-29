# U-Net Image Segmentation with Otsu's Thresholding

This Jupyter Notebook demonstrates the use of a U-Net model for image segmentation, combined with Otsu's thresholding for image binarization. The notebook includes the following steps:

1. **Importing Libraries**: Import necessary libraries including NumPy, Matplotlib, scikit-image, and Keras.
2. **Defining the U-Net Model**: Create a U-Net model using Keras.
3. **Otsu's Thresholding**: Apply Otsu's thresholding using scikit-image.
4. **Prediction with U-Net**: Use the U-Net model to predict the segmentation mask for the input image.
5. **Plotting Results**: Visualize the original grayscale image, the binary image obtained using Otsu's thresholding, and the U-Net output.

## Cells Description

- **Cell 0**: Import necessary libraries.
- **Cell 1**: Define the U-Net model architecture.
- **Cell 2**: Define a function to apply Otsu's thresholding using scikit-image.
- **Cell 3**: Define a function to predict the U-Net output.
- **Cell 4**: Define a function to plot the results.
- **Cell 5**: Load and preprocess the image, apply Otsu's thresholding, predict with U-Net, and plot the results.

## Usage

1. **Load Image**: Replace `"path_to_your_image.jpg"` with the path to your image file.
2. **Run Cells**: Execute the cells in order to see the results.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- scikit-image
- Keras
- TensorFlow (backend for Keras)

## Example

The notebook processes an image, applies Otsu's thresholding, and uses a U-Net model to segment the image. The results are visualized in a plot showing the original grayscale image, the binary image from Otsu's thresholding, and the U-Net output.
