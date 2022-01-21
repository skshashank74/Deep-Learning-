# Deep Learning Systems

## Assignment 1:

The assignment deals with doing an experimental analysis using linear neural network classification by changing different hyperparameters and testing the accuracy. We used different optimizers, initializer, activation function, learning rate, nodes and layers to do this experimentation. 

Also, this experimentation involves to study how each layer is contributing to differentiating  the different classes. We performed T-SNE and PCA to the output of each layers and see how the segregation is happening. 

## Assignment 2:

The assignment deal with speech denoising. We first use an ANN architecture to perform denoising. We created a spectrogram of the voice notes by doing stft and then pass it to an ANN architecture. After this, we deep dive into convolutional neural networks to perform the same task. We first use 1-D convolution followed by 2-D convolutions. We compare the results of each architecture.

## Assignment 3:

There were three parts to do this assignment. First question was related to data augmentation. The task was to study how creating more training data by performing techniques like data augmentation can increase the accuracy of the task. We used CIFAR data set. In second question, we used transfer learning and data augmentation techniques to increase the performance of the networks. We initialized the weights of our final classifier using the weights from a different architecture which was used to perform a similar task but by using different techniques.

In the third question we had to speech denoising using LSTM. The dataset of this problem statement was little complicated. The length of the signal in the input varied a lot and simple padding affects the loss greatly as we needed to pad the output (clean signal) too. We used a different preprocessing technique where we divided the signals into batches of 10 and padded those signals which had less than 10 frames. This way we reduced the amount of padding

## Assignment 4:

First three problems in the assignment were based on network compression. We used different variation of network compression technique to reduce the storage space of the weights without effecting the accuracy. In one of the techniques, we were able to compress the network by 97% without decreasing the accuracy of the model.

Fourth problem deals with Siamese network for one shot speech detection. We had 500 signals (50 unique speakers each having 10 signals) and we needed to identify which speakers each of the signal belongs to in the test data. Siamese networks use a twin network architecture. The parameters between the two subnetworks are tied and based on cosine similarity it identifies which two signal are same.

## Assignment 5:

This assignment deals with image generation task:

First question: Trained an LSTM model which generated lower half of the image by taking previous frame of image as an input. Compared the results with actual lower half of the image

Second question: Created latent vectors for image data using Variational Autoencoders. Cross validated how close to real images the decoders were generating images based on randomly initialized latent vectors. We then identified which latent dimension influence rotation in the image.

Third question: Generated a complete image giving center patch of the image as input to the conditional GANS

Fourth question: Missing value imputation of an image using GANS

