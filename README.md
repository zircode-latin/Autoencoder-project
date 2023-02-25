# Autoencoder-project
The main objective of this project is to segregate mulberry leaves using an intelligent monitoring platform framework. 

Image processing techniques and deep learning concepts are used to achieve this purpose. Integration of both hardware and software makes the work easier.

The major task here is collecting the data which hat is images of healthy and diseased leaves which is used to train our model. Some of the major steps involved in the entire process are as follows:
• Image acquisition
• Pre-processing,
• Segmentation,
• Feature extraction and
• Classification.

Captured images of leaves are sent to pre-processing check. Here image resizing, leaf detection, and noise removal take place. Image cropping to the specified dimension, thresholding, and masking are done in Segmentation.

For feature extraction, color, shape, and texture are considered global descriptors. These vectors are extracted from both training and test images
separately and are fed as input to the classifiers for the classification. 

We make use of different algorithms which compare separately, comparing the training vectors and test vectors, and report the results.
