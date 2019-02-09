# InstaRF Proposal

## Contributors:

Betty Zhou     
Linyang Yu    
Reza Bagheri    
Simon Chiu    

## Overview

Image processing uses computer algorithms to enhance an image or to extract useful information from it. In this package, we have implemented some R functions for image processing. These functions perform Gaussian blurring, Laplacian edge detection, and color changing.

## Functions

1. **Gaussian Blur**    
   This function performs convolution to de-emphasize differences in adjacent pixel values with a Gaussian distribution. The blurring effect removes detail and noise in the input image.
2. **Laplacian Edge Detecting**    
   This function performs convolution to emphasize differences in adjacent pixel values. The function detects edges by sharpening/highlighting the edges of an image.
3. **RBG Manipulation**    
   This function adjusts the red, blue and green intensity of an image by applying different weights for each RBG channel. This is similar to a colour filter in Instagram.

## R Ecosystem

[InstaR]( https://github.com/UBC-MDS/InstaR/tree/v4.0) is a R package that contains the three functions: blur, flip and greyscale to transform images. In this project, we plan to implement three more image processing functions in R by exploring additional filters.

## Repo Structure (updating)

InstaRF: repo root
  * InstaRF: package formatting, including dvtool files.
    * R: [R](InstaRF/R/) folder contains most of our function files, now all the functions are defined but empty, only with doc string;
  * test_r: folder contains all our test .R file.
    * test_image: contains all the testing image we will use;
    * [test_RGB_manipulation.R](test_r/test_RGB_manipulation.R)
    * [test_Laplacian_edge_detecting.R](test_r/test_Laplacian_edge_detecting.R)
    * [test_gaussian_blur.R](test_r/test_gaussian_blur.R)
  * [CONTRIBUTING.md](CONTRIBUTING.md)
  * [Code_of_CONDUCT.md](Code_of_CONDUCT.md)