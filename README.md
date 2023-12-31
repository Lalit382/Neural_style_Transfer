# Neural_style_Transfer
Implementation of Neural style transfer
Neural Style Transfer Implementation
This code implements neural style transfer, a technique for transferring the style of one image to another. The code is based on the paper "A Neural Algorithm of Artistic Style" by Gatys et al. (2015).


Prerequisites
The code requires the following libraries:

TensorFlow 2.x
NumPy
Matplotlib
IPython.display

Instructions
To run the code, follow these steps:

1.Download the code and save it as neural_style_transfer.py.
2.Download the content image and style image and save them in the same directory as the code.
3.Open a terminal window and navigate to the directory containing the code.
Run the following command:
python neural_style_transfer.py
The code will train a model to transfer the style of the style image to the content image. The stylized image will be displayed in a new window.

Code Overview
The code is divided into the following sections:

1.Importing necessary dependencies: This section imports the required libraries.
2.Preprocessing of the Images: This section defines a function to load and preprocess images.
3.Function to display an image: This section defines a function to display an image.
4.Loaded a VGG19 model pre-trained on ImageNet data for features of the corresponding style and content images: This section loads a pre-trained VGG19 model.
5.Function to provide the outputs of a particular convolutional layer of VGG19: This section defines a function to extract the outputs of a particular 
  convolutional layer of VGG19.
6.Choose intermediate layers from the network to represent the style and content of the image: This section selects the layers from the VGG19 model to represent 
  the style and content of the images.
7.Create the model: This section creates a model that extracts the style and content features from the input image.
8.Class definition to execute different functionalities: This section defines a class that encapsulates the functionality of the model.
9.Define weights for style and content loss as prposed by Gaty's et al. as: This section defines the weights for the style loss and content loss.
10.Run gradient descent: This section performs gradient descent to optimize the image for style transfer.
11.Update the image with style: This section updates the image with the style of the style image.
12.Display the stylized image: This section displays the stylized image.

Additional Notes
1.The code can be modified to use different layers from the VGG19 model.
2.The code can be modified to use different weights for the style loss and content loss.
3.The code can be modified to use a different optimization algorithm.
