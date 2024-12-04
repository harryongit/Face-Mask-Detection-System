# Face Mask Detection System

This project is a Convolutional Neural Network (CNN)-based system to classify whether a person is wearing a face mask or not. It uses the Keras deep learning library with TensorFlow as the backend. The system processes images and can also be applied to real-time video streams for face mask detection.

---

## Features

- **Real-time Face Mask Detection**: Detects faces in images or video streams and classifies whether they are wearing a mask.
- **Customizable Training**: You can train the model with your own dataset.
- **Binary Classification**: Outputs "Mask" or "No Mask".
- **Data Augmentation**: Augments the dataset by applying transformations such as rescaling, flipping, and zooming during training.
- **Pre-trained Model**: The trained model is saved and can be reused for predictions.

---

## Requirements

Ensure that Python 3.7 or later is installed. The following Python libraries are required:

- `opencv-python`
- `keras`
- `tensorflow`
- `matplotlib`

To install these dependencies, run the following command:

```bash
pip install opencv-python keras tensorflow matplotlib
