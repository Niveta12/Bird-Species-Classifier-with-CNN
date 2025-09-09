# Bird Species Classifier with CNN
This project uses a Convolutional Neural Network (CNN) to classify 20 different species of birds from images.

📌 **Features**
1. CNN architecture for image classification.

2. Training and evaluation pipeline using TensorFlow and Keras.

3. Data Augmentation using ImageDataGenerator.

4. Metrics: Accuracy and Loss.

5. Jupyter Notebook implementation using GoogleColab.


**Methodology:**

The model is built using TensorFlow and Keras, with multiple convolutional and max pooling layers for feature extraction. It also includes a fully connected layer for classification and uses the ReLU activation function for non-linearity. The output layer uses a softmax activation function to provide probability distributions across the classes.

**Data:**

The dataset consists of 3,208 training images, 100 validation images, and 100 test images, belonging to 20 classes. The images were processed using ImageDataGenerator with a target size of 128x128 pixels.

🧪 **Evaluation:**

The initial CNN model achieved a validation accuracy of 74% and a test accuracy of 68%.

Using the pre-trained Inception V3 model, the project achieved an accuracy of 96.48% with a loss of 32.41%, and a validation accuracy of 92%.
