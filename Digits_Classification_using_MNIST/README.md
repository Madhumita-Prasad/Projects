

# Digit Classification using Neural Networks

# **Overview**
This script demonstrates a neural network-based approach for handwritten digit recognition using the MNIST dataset. It includes steps for data preprocessing, model training, evaluation, and real-time prediction of handwritten digits from user-provided images.

---

## **Features**
1. **Data Preprocessing**:
   - Loads the MNIST dataset and scales the pixel values to the range [0, 1].
   - Displays sample images and corresponding labels for visualization.

2. **Model Architecture**:
   - A neural network with:
     - Input layer (flattened 28x28 pixels),
     - Two hidden layers (50 neurons each, ReLU activation),
     - Output layer (10 neurons, sigmoid activation for classification).

3. **Model Training**:
   - Trains the model using `Adam` optimizer and `sparse_categorical_crossentropy` loss function.
   - Performance metrics include accuracy.

4. **Evaluation**:
   - Evaluates the model on the test dataset and computes predictions.
   - Displays a confusion matrix to analyze prediction performance.

5. **Real-time Prediction**:
   - Allows users to provide custom digit images for prediction.
   - Preprocesses the image and predicts the digit using the trained model.

---

## **Requirements**
- Python 3.x
- Required libraries:
  - `tensorflow`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `cv2` (OpenCV)
  - `PIL` (Python Imaging Library)

---

## **Usage**
1. **Setup**:
   - Ensure the required libraries are installed.
   - Save the script as `digit_classification.py`.

2. **Run the Script**:
   - Execute the script in a Python environment (e.g., Jupyter Notebook, Google Colab, or a local terminal).
   - The model will train on the MNIST dataset and display evaluation metrics.

3. **Custom Prediction**:
   - Provide the path to a custom image (e.g., a handwritten digit saved as `.png`).
   - The script processes the image and predicts the digit.

---

## **Advantages**
- Easy-to-use script for beginners and researchers.
- Demonstrates practical application of neural networks for image classification.
- Modular design for training, evaluation, and prediction.

---

## **Limitations**
- Limited to grayscale 28x28 pixel images.
- Custom image preprocessing must align with MNIST standards.
- The model’s architecture is simple and may not generalize well to complex datasets.

---

## **Acknowledgments**
- **Dataset**: MNIST dataset from the `keras.datasets` module.
- **Tools**: Python libraries including TensorFlow and OpenCV.

---

## **Author**
- Automatically generated from a Google Colab notebook.

--- 

Feel free to adapt this README to suit your exact requirements!
