# Neural Style Transfer
Neural Style Transfer is a technique that combines the content of one image with the artistic style of another image. It uses deep neural networks to generate visually appealing images that blend the content and style in a unique way. This repository provides an implementation of Neural Style Transfer using Python and the popular deep learning library, PyTorch.

## Model Architecture
The model architecture for Neural Style Transfer using CNN typically involves using a pre-trained convolutional neural network as a feature extractor. The most commonly used architecture for this purpose is the VGG (Visual Geometry Group) network. Specifically, VGG-19, which is a deep convolutional network with 19 layers, is commonly utilized in Neural Style Transfer.

The style loss is computed by comparing the Gram matrices of the generated image and the style image at each selected layer. The content loss is computed by comparing the feature maps of the generated image and the content image at a specific layer.

## Results

### Content and Style Images
![](https://github.com/Rutvik1727/Neural-Style-Transfer/blob/main/Images/NST%20(2).png)

### After Style Transfer
![](https://github.com/Rutvik1727/Neural-Style-Transfer/blob/main/Images/NST%20(1).png)
