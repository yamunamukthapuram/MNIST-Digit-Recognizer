
# Handwritten Digit Recognition

This project utilizes a neural network to recognize handwritten digits (0-9) from images, leveraging the MNIST dataset for training and evaluation.

## Features

- Image Classification: Classifies handwritten digits from images.
- Model Training: Trains a neural network model using the MNIST dataset.
- Model Evaluation: Assesses the model's performance on test data.
- Image Prediction: Allows users to input custom images for digit prediction.

## Folder Structure

Handwritten Digit Recognition/
├── dataset/            
├── model/              # Saved trained model
├── images/             # Example handwritten digits
├── main.ipynb          # Jupyter notebook with training/testing code
├── requirements.txt    # Required Python packages
└── README.md           # Project documentation

## Installation

1. Clone the repository:

   git clone https://github.com/yamunamukthapuram/Handwritten-Digit-Recognition.git
   cd Handwritten-Digit-Recognition

2. Install dependencies:

   pip install -r requirements.txt

## Usage

1. Open main.ipynb in Jupyter Notebook.
2. Run the cells to:
   - Load the MNIST dataset.
   - Train the model (or load a pre-trained model).
   - Test handwritten digit images.
3. The model predicts the digit in the input image.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- OpenCV (optional, for image preprocessing)

## License

This project is open-source and free to use.
