The model used to denoise any image using auto-encoders.

## <b>Auto-Encoders:</b> 
Autoencoders are an unsupervised learning technique in which we leverage neural networks for the task of representation learning. Specifically, we'll design a neural network architecture such that we impose a bottleneck in the network which forces a compressed knowledge representation of the original input. If the input features were each independent of one another, this compression and subsequent reconstruction would be a very difficult task. However, if some sort of structure exists in the data (ie. correlations between input features), this structure can be learned and consequently leveraged when forcing the input through the network's bottleneck.

## Install
pip install tensorflow<br/>
pip install matplotlib<br/>


## About Libraries
<h3><b>Tensorflow:</b></h3> TensorFlow is an end-to-end open source platform for machine learning.
<p></p>

<h3><b>Matplotlib:</b></h3> Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.
<p></p>

## Dataset: 
The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset.

It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

## Procedure:
The images are loaded and then a random noise is added to all the images to create training data

## Models:
1) Using auto-encoders by maintaining 2-dimensional shape of the image.
2) Using auto-encoders by converting 2-dimensional image to 1-dimensional vector and then reverse formation of image.



