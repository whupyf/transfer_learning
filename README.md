# Summer Project 2021
## Transfer Learning
use pre-trained resnet-18 to classify face image
### baseline model
re-train the softmax layer
### model A
Fine tune Conv5_x
### model B
Fine tune Conv4_x and Conv5_x
### model C
Fine tune Fine tune ALL convolution layers
### model D
Freeze all the convolution blocks, introduce two FC layers prior to the softmax layer and train them together with softmax layer
