# image-proceesing

Implementing the Image Processing Filters
The following is a list of features that you need to implement (listed roughly from easiest to hardest). Refer to the http://bit.ly/2IXuKjS for more details on the implementation of each filter and example output images.

Luminance Operations
Brightness : Change the brightness of an image by scaling RGB values by a factor. Contrast : Change the contrast of an image using the method described in http://bit.ly/2wWVtrQ .

Linear Filtering Operations
Blu r : Blur an image by convolving it with a Gaussian low - pass filter. Sharpen : Apply a linear sharpening filter to the image. Edge detect : Detect edges in an image by convolving it with an edge detection kernel.

Resampling Operations
Scale : Scale an image up or down in resolution by a real valued factor.

Composite Operations
Composite : Compose one image with a second image using the over operator, with a third image as a matte (alpha). To get full credit for any of the operations requiring resampling (scale), you must support three different sampling methods (point, linear, and Gaussian) and compare the results for at least one example. The sampling method to be used by imgpro is control led by arguments specified before the resampling operation on the command line. For example, imgpro in.jpg out.jpg - point_sampling - rotate 1 - gaussian_sampling rotate 3 will rotate the input image by 1 radian using point sampling and then rotate the res ult by 3 radians using Gaussian sampling. For Gaussian sampling, choose sensible Gaussian filter dimensions. For scaling, this requires adapting the extent of the Gaussian
