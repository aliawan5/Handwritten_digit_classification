# Handwritten_digit_classification
This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The notebook is organized into the following sections:

Dataset
The MNIST dataset, a collection of 70,000 grayscale images of handwritten digits (0-9), is used. Each image is 28x28 pixels.

Notebook Sections
1. Importing Libraries
The necessary libraries such as numpy, matplotlib, seaborn, tensorflow, and keras are imported.

2. Loading the Data
The MNIST dataset is loaded from keras.datasets. The dataset is split into training and testing sets.

3. Data Preprocessing
Data normalization is performed to scale pixel values to the range [0,1]. Additionally, the training data is reshaped to fit the input shape expected by the CNN.

Flatten: Flattening the pooled feature maps
Dense: Fully connected layers for classification

5. Compiling the Model
The model is compiled with the Adam optimizer, sparse categorical cross-entropy loss function, and accuracy as a metric.

6. Training the Model
The model is trained on the training data for 10 epochs with a batch size of 128. Validation is performed using the test data.

7. Evaluating the Model
The model's performance is evaluated using the test data. The accuracy and loss are reported.

8. Confusion Matrix
A confusion matrix is generated to visualize the performance of the model across different digit classes.

Conclusion
This project demonstrates the implementation of a CNN for handwritten digit recognition using the MNIST dataset. The high accuracy indicates the model's effectiveness in recognizing handwritten digits.

