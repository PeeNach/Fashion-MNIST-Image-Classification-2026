# Fashion-MNIST-Image-Classification-2026

## Google Colab Link: https://colab.research.google.com/drive/1DjJRWiVcUAJxyjSO8EZVDKW85jS3-oXq?usp=sharing

1. What is the Fashion MNIST dataset?
- The Fashion MNIST dataset is a collection of 70,000 grayscale images of clothing items.
- Each image is 28×28 pixels and belongs to one of 10 clothing categories.
- It is commonly used to train and test image classification models.

2. Why do we normalize image pixel values before training?
- Normalization scales pixel values from 0–255 to a range of 0–1.
- This helps the model train faster and more accurately.
- It also improves numerical stability during training.

3. List the layers used in the neural network and their functions.
- The Flatten layer converts the 2D image into a 1D array.
- The Dense (128) layer learns patterns using the ReLU activation function.
- The Dense (10) output layer produces scores for the 10 clothing classes.

4. What does an epoch mean in model training?
- An epoch means one complete pass of the entire training dataset through the model.
- During each epoch, the model updates its weights to reduce error

5. Compare the predicted label and actual label for the first test image.
- The predicted label is the class chosen by the model.
- The actual label is the true class from the dataset.
- If they match, the prediction is correct; otherwise, it is incorrect.
6. What could be done to improve the model’s accuracy?
- The model accuracy can be improved by increasing the number of epochs.
- Adding more hidden layers or using a convolutional neural network (CNN) can help.
- Tuning hyperparameters such as learning rate may also improve performance.
