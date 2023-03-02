# Neural Style Transfer

Neural style transfer is an interesting application of transfering the style of an art onto an image. We use deep learning to understand the characteristics of the artistic image, and then use it to transfer it to the image. Some inputs and their corresponding results are here (They are breathtaking)

## Inputs
![inputs](nst.jpg)

## Results
![results](results.jpg)

# How does this work?

We do not train a neural network for transferring the style. Rather, we use the content image and the style image and slowly transfer the style to it, iteratively. We have a content loss that uses the internal activations of VGGNet, to find the difference in both images, sort of like a similarity measure. Thus, our content image has the gradient and we modify that image. 
