Median filtering is a nonlinear process useful in reducing impulsive, or salt-and-pepper noise. The median filter is also used to preserve edge properties while reducing the noise. Also, the smoothing techniques, like Gaussian blur is also used to reduce noise but it can’t preserve the edge properties. The median filter is widely used in digital image processing just because it preserves edge properties.

Approach :

Store the pixel values of input image in an array.
For each pixel value store all the neighbor pixel value including that cell in a new array (called window).
Sort the window array.
Median of window array is used to store output image pixel intensity.

![input](https://user-images.githubusercontent.com/55890344/97770680-742cd080-1b5b-11eb-8790-1b93d8513fc7.png)
