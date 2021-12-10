# Image Processing I

## Project 1
In this project we were tasked with the following: 
Use the image given below to map the intensity to the full dynamic range of 0-255.
1. First find the min and max values from the image for one of the three bands (since it is gray level
image all three bands will have same pixel intensities at a given location).
2. The intensity range can be mapped to full range (0-255) by a simple mapping function (H) which
maps the input pixel intensity min to 0 and max to 255. Derive the mapping function and
implement using python arrays and for loops.

![1](https://user-images.githubusercontent.com/62857780/145594456-e107ed3a-f3f9-40ad-8e3c-f3ecd736fb38.png)

## Project 2
In this project we were tasked with the following: 
Given the image of Lena, the goal of the assignment is to enlarge the image by a factor of k (where k = (k = 2,
2.5, 3.0,3.5, 4.0 along both dimensions) using the following interpolation techniques.
1. Nearest Neighbor interpolation
2. Bilinear interpolation

![lena64](https://user-images.githubusercontent.com/62857780/145594684-14f7c8b1-4db7-4cd9-a8be-0897f7d3300b.jpg)

## Project 3
The goal of this project was threefold:
1. Derive piece wise transformation equations s = T(r) for the following piecewise linear
transformation between input gray r and output gray s. The control points are given as: (0,0)
(40,80) (100,250) using the image provided
2. Write a function that transforms input intensity r to output intensity s using piecewise linear
transform as given above. where r is input intensity and s is output s intensity. Assume the
dynamic range r is 0-100 and s is 0-250. Apply the above piece-wise linear transformation on
washdc512.jpg image and show the results.
3. Apply Gamma-Correction using the following mapping function on the same image and show
the results for various values of gamma (Assume c = 1.0 and γ = 1.5, 0.5) s = c r γ

![1](https://user-images.githubusercontent.com/62857780/145594456-e107ed3a-f3f9-40ad-8e3c-f3ecd736fb38.png)

## Project 4
The goal of this project was to improve the provided image contrast using the
histogram equalization.

![1](https://user-images.githubusercontent.com/62857780/145594456-e107ed3a-f3f9-40ad-8e3c-f3ecd736fb38.png)

## Project 5
The goal of this project was threefold:
a) For the image given below (arya.jpg) add random Gaussian noise (mean = 0.0, sigma = 20.0) and
generate array of 10 noisy images.
b) Compute average of the 10 images by adding them pixel by pixel and dividing the result by 10. This
should be able to clean up the image by suppressing the random noise.
c) Display at least 6 noisy images and finally the clean image

![arya](https://user-images.githubusercontent.com/62857780/145595201-7ea842e8-787c-442f-8c18-d8b39f8cd525.jpg)

## Project 6
The goal of this assignment was two-fold:
a) Smooth the noisy image attached by using a mean (average) filter in 3x3 window iteratively until
satisfactory results are obtained. Show the results for 1 5 10 iterations.
b) Do some research on median filters and advantage of median filter over mean filter. Apply median
filtering in 3x3 window to smooth the noisy image given below and, iterate 1, 5, 10 times and show the
results. Write your conclusions after you compare the results from average filter and median filter

![lena64](https://user-images.githubusercontent.com/62857780/145594684-14f7c8b1-4db7-4cd9-a8be-0897f7d3300b.jpg)

## Project 7
The goal of this assignment was three-fold:
Enhance edges of the following image using:
a) Roberts cross operator (Please read Roberts cross operator from the book)
b) Sobel’s operator
c) Apply Laplacian operator in 3x3 window and show the results.

![1](https://user-images.githubusercontent.com/62857780/145594456-e107ed3a-f3f9-40ad-8e3c-f3ecd736fb38.png)


