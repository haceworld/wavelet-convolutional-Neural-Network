# wavelet
Wavelet convolutional neural network combines a multiresolution analysis and convolutional neural network into a single model to achieve computer vision task.

# Description wavelet convolutional neural network connectivity
Overview of wavelet CNN with 4-level decomposition of the input image. Wavelet CNN processes the input image through convolution layers with 3 × 3 kernels and 1 × 1 padding. The number after Conv denotes the number of channels of the output. 3 × 3 convolutional kernels with the stride of 2 and 1 × 1 padding are used to reduce the size of feature maps. Additionally, the input image is decomposed through multiresolution analysis and the decomposed images are concatenated channel-wise. The projection shortcuts are done by 1 × 1 convolutions. The output of convolution layers is vectorized by global average pooling followed by a fully connected layer (fc). The size of the output is equal to the number of classes included in the input dataset. Click here to read the paper

# Multi-Resolution Analysis of Discrete Wavelet Transform Decomposition
For 2-dimensional image input, Multi-Resolution Analysis of Discrete Wavelet Transform Decomposition is applied as a technique to decomposed the image into approximate and detail coefficient of varying frequencies and scales through low- and high-pass filters with the scale factor of 2. The approximat coefficient is the low frequency component while the detail coefficient is the high frequency component.
