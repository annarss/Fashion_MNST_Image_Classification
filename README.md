1.What is the Fashion MNIST dataset? The Fashion MNIST dataset contains 28×28 grayscale images of different clothing items such as shirts, pants, shoes, and bags. It includes 60,000 training images and 10,000 testing images and is commonly used for image classification tasks instead of the original MNIST digits dataset.

2.Why do we normalize image pixel values before training? We normalize pixel values from 0–255 to 0–1 so the model can train faster and more efficiently. This helps improve learning stability and allows the optimizer to perform better during training.

3.List the layers used in the neural network and their functions. The image is transformed into a one-dimensional array by the Flatten layer. The final Dense layer outputs the prediction scores for the ten clothing classes, while the Dense layers with Relu activation extract patterns from the data.

4.What does an epoch mean in model training? One complete run of the training dataset through the model is called an epoch. The model learns more effectively with more epochs, but overfitting may result from using too many.

5.Compare the predicted label and actual label for the first test image. The model correctly classified the first test image since the predicted and actual labels matched. This demonstrates that the category for that sample was correctly identified by the trained neural network.

6.What could be done to improve the model’s accuracy? Increasing the number of epochs, adding more hidden layers, changing the number of neurons can all increase accuracy.
