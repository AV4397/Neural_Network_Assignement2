CS5720 Neural Network and Deep Learning - Home Assignment 2 Student Information

Name: Veda Arvind Kumar

Student ID: 700774397

Course: CS5720 Neural Network and Deep Learning

Semester: Spring 2025

University: University of Central Missouri

Project Overview

This assignment focuses on performing convolution operations with various strides and paddings, applying Sobel filters for edge detection, demonstrating pooling techniques, and building convolutional neural network (CNN) architectures including AlexNet and a ResNet-like model. Each task aims to deepen understanding of fundamental deep learning techniques.

Code Description

1. Convolution with Different Parameters

Conducted convolution operations on a 5×5 input matrix using a 3×3 kernel.

Explored the following stride and padding configurations:

Stride = 1, Padding = 'VALID': No padding, output size reduced.

Stride = 1, Padding = 'SAME': Output size matches input, padding added.

Stride = 2, Padding = 'VALID': Downsampling without padding.

Stride = 2, Padding = 'SAME': Downsampling with padding to maintain size consistency.

Feature maps were printed for each case, showcasing the impact of stride and padding on the output dimensions.

2. Sobel Filter Edge Detection

Sobel-X and Sobel-Y filters were explicitly defined and applied to detect vertical and horizontal edges, respectively.

The provided image was processed using OpenCV's filter2D function, with results visualized using Matplotlib.

The output showcased clear edge detection patterns.

3. Pooling Operations

Performed max pooling and average pooling operations on a randomly generated 4×4 matrix.

Max pooling demonstrated feature reduction by selecting maximum values.

Average pooling showcased smoothing by computing mean values in each pooling window.

Output matrices validated the expected dimensionality reductions.

4. CNN Architectures

AlexNet Implementation:

Comprised multiple convolutional, max-pooling, dense, and dropout layers.

Model summary highlighted the flow of feature maps and layer parameters.

ResNet-like Model:

Integrated residual blocks to demonstrate skip connections, preventing vanishing gradients.

Each residual block processed input through convolutional layers, adding the output back to the input tensor.

Results

Convolution feature maps successfully visualized under various stride and padding settings.

Sobel filter outputs demonstrated effective edge detection along vertical and horizontal axes.

Pooling operations reduced matrix dimensions as expected, validating spatial reduction concepts.

CNN architectures (AlexNet and ResNet-like) printed comprehensive model summaries, confirming proper layer connections and configurations.

Git repository Link - https://github.com/AV4397/Neural_Network_Assignement2/
