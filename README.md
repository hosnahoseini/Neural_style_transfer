
# Neural Style Transfer
Inputs:

![image](https://github.com/hosnahoseini/Neural_style_transfer/blob/main/1.png)


Result:

![image](https://github.com/hosnahoseini/Neural_style_transfer/blob/main/2.png)

## Introduction
Neural style transfer is an optimization technique that allows you to transfer the artistic style of one image to another image. This can be used to create a variety of artistic effects, such as turning a photograph into a painting or a sketch.

## Learning Objectives
In this project, I implement neural style transfer using the VGG-19 convolutional neural network. I also learn how to compute the content and style loss functions and minimize them using optimization techniques.

## Steps
1- Load pretrained VGG-19 model: Download the pretrained VGG-19 model from TensorFlow Hub.

2- Extract content and style features: Extract content features from the content image and style features from the style image using the VGG-19 model.

3- Create style and content loss function: Define the content loss function and the style loss function. The content loss function measures the difference between the content features of the content image and the content features of the generated image. The style loss function measures the difference between the style features of the style image and the style features of the generated image.

4- Minimize the total loss: Minimize the total loss, which is the sum of the content loss and the style loss, using an optimization technique such as Adam.

5- Generate artistic style image: Save the generated image.

## Library we used in this project:
- TensorFlow
- NumPy
