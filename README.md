nnunet PlainConvUNet‘s unet_decoder file, I added a Category prediction branch, may worked. 
Task 2 uses the model weights from Task 1, takes the input points as one input channel, and trains the network to produce two newly added output channels.
The preprocessing was implemented using MONAI, but it seems that my designed processing did not have the intended effect and requires further testing.
