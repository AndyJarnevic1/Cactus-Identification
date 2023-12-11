# Cactus-Identification

# Description:

Using Keras deep learning techniques to decide whether an aerial image contains a cactus.

# Method:

The model architecture uses two convolution layers with 20 and 15 layers respectively, each using a rectified linear unit activation function. The outputs are then fed into a dense output layer using sigmoid activation to make the predictions. The model is optimized using adam, and early stopping is used to stop optimizing after two epochs fail to show improvement. This should help to prevent overfitting.

# Results:

This model achieved a remarkable 0.996 AUC score. 

# Skills Used:

-Keras \
-TensorFlow \
-Image Processing \
-Callbacks \
-Image Manipulation
