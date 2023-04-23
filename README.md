# PSNR-calculation

This program written in python can calculate Peak Signal-to-noise-ratio between two images.  

Peak signal-to-noise ratio(PSNR) is an engineering term for the ratio between the maximum possible power of a signal and the power of corrupting noise that affects the fidelity of its representation.


Features  

Adding noise to an image  

Various noise like SALT and PEPPER, GAUSSIAN, POISSON, SPECKLED NOISE.   
1. Gaussian Filter:   
 
In image processing, a Gaussian blur (also known as Gaussian smoothing) is the result of blurring an image by a Gaussian function (named after mathematician and scientist Carl Friedrich Gauss). It is a widely used effect in graphics software, typically to reduce image noise and reduce detail.     

2. Mean Filter:  

Mean filter is a simple sliding window that replace the center value with the average of all pixel values in the window. The window or kernel is usually a square but it can be of any shape.    

3. Median Filter:  

Mean filter is a simple sliding window that replace the center value with the Median of all pixel values in the window. The window or kernel is usually a square but it can be of any shape.  
  
4. The Wiener filter
The Wiener filter is the MSE-optimal stationary linear filter for images degraded by additive noise and blurring. Calculation of the Wiener filter requires the assumption that the signal and noise processes are second-order stationary (in the random process sense).  


Filters like mean,median,weiner,guassian were used to remove these noises.  

PSNR values is calculated between the original and filtered imagess.
