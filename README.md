# Cactus-Identification

# Description:

Using Keras deep learning techniques to decide whether an aerial image contains a cactus.

# Method:

The model architecture uses two convolution layers with 20 and 15 layers respectively, each using a rectified linear unit activation function. The outputs are then fed into a dense output layer using sigmoid activation to make the predictions. The model is optimized using adam, and early stopping is used to stop optimizing after two epochs fail to show improvement. This should help to prevent overfitting.

# Results:

This relatively simple model achieved a 0.98 AUC score. While there is still room for imporvement, this is a remarkably good score for a model with only two hidden layers.

# Skills Used:

-Keras
-TensorFlow
-Image Processing
-Callbacks

# Next Steps:
In order to improve the performance of this model, there are two main directions I'd like to persue. The first is to experiment with different (deeper) architectures and see if the added expressivity of these models can overcome their propensity to overfit the training data.
The second idea is to artificially increase the size of the training data by manipulating the images. Rotations should not affect the output of the model, so I will try to add rotated versions of the photos to the training set and see if this new data can improve the models performance.
