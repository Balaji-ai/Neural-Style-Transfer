# Neural-Style-Transfer
Neural Style Transfer using pretrained CNN (VGG-19)
1. Load the VGG-19 network.
2. Create a function which converts image into tensor.
3. Create a function which reconverts tensor back into image.
4. Create a function which can extract feature maps from the VGG-19
model given a tensor
( ‘conv1_1’, ‘conv2_1’, ‘conv3_1’, ‘conv4_1’, ‘conv5_1’ – Style features
‘conv4_2’ – Content features).
5. Calculate the total loss, given functions which can calculate Content
loss and Style loss. To calculate style loss, we need to create a function
which can calculate correlation across different channels of all the Style
feature maps.
6. We can either use a content image or white noise (target image) to arrive
at the generated image. We update the individual pixelvalues of the target
image by using Gradient descent.
