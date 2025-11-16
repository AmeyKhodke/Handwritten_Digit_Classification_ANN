Handwritten Digit Classification using ANN
This project implements an Artificial Neural Network (ANN) to classify handwritten digits using the MNIST dataset. The process includes loading the dataset, preprocessing images, building an ANN model, training it, evaluating its accuracy, and making predictions on handwritten digits.

📌 Project Overview
This project covers:
Loading the MNIST handwritten digit dataset
Normalizing image pixel values
Building an ANN using Dense layers
Training the model using categorical crossentropy
Evaluating model performance (accuracy & loss)
Predicting digits from the test dataset

🧠 Model Architecture
The Artificial Neural Network used in this project has:

Input Layer:
Flatten layer that converts 28×28 images to 784 inputs

Hidden Layer 1:
Dense(128 units, activation='relu')

Hidden Layer 2:
Dense(64 units, activation='relu')

Output Layer:
Dense(10 units, activation='softmax')
Outputs probabilities for digits 0–9

🛠 Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
