# Denoising-Noisy-Images
This notebook uses a public dataset from kaggle.
The dataset consists of images where each image consists of some text having some added noise.
The task of the model is to reduce/remove the present noise in the images.

The model makes use of Autoencoders and Decoders.
Here each image is encoded using a Convolution layer and a Max Pooling layer.
Then each image is decoded using a convolution layer and a Up Sampling layer.
Then the final image is generated using a Convolutional layer.
The image generated in last is a denoised image.
