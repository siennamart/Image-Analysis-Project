Neural Network-Based Image Classification of MNIST Digits 4 and 9

Overview
This project focuses on developing a neural network-based image classification algorithm to distinguish between the digits 4 and 9 in the MNIST dataset. 
The project includes data filtering, model definition, training, and evaluation to achieve high accuracy in recognizing these specific handwritten digits.

Analysis Steps
We began by loading the MNIST dataset, which contains images and labels for handwritten digits. To focus on the digits 4 and 9, we created boolean
masks to filter the dataset accordingly. The filtered datasets were then normalized by scaling the pixel values to a range of 0 to 1.
Next, the images were reshaped from their original 3D arrays (28x28) to 2D arrays (784,) to be compatible with our neural network model.
We defined the model using Keras, incorporating appropriate layers for the classification task. The model was then trained on the filtered and normalized dataset, 
with a focus on minimizing validation loss. Finally, we evaluated the trained model on the test dataset to assess its accuracy in classifying the digits 4 and 9.

File Description
The file t10k-images.idx3-ubyte.zip contains the necessary data and code to perform the data analysis, including the steps mentioned above.
It includes the implementation of the neural network model, data preprocessing, training, and evaluation scripts.
