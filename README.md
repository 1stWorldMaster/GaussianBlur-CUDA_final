# CUDA Parallel Gaussian Blur
This program will apply a Gaussian blur to the specified image. This is accomplished by convolving the target image with the Gaussian function. To the user, the resulting image will have been uniformly blurred, which can be helpful in many other algorithms such as blob detection and downsampling.


OpenCV is necessary for this program to work. While all image processing is done by standard C++ and CUDA libraries, retrieving image properties is made significantly easier by OpenCV.

