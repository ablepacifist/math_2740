# Assignment 12: SVD Compression of **coolAlex.bmp**
### Author: Alexander Dyakin  
#### ID: 7828027  
#### Section: B01  
---

## About
The `assignmet12.Rmd` program computes the **Singular Value Decomposition (SVD)** of an image, **coolAlex.bmp**. It compresses the image using 30 singular values via R's native SVD function and compares the original image with the compressed version in terms of pixel count.

## Important Notes
- The file **coolAlex.bmp** is not included in the submission folder due to file type restrictions.  
- To download it, visit [this link](https://github.com/ablepacifist/math_2740/).  

## How to Run
1. Place `assignmet12.Rmd` and **coolAlex.bmp** in the same directory.  
2. Open the file in RStudio and run the program.  

## Required Libraries
Install the following libraries before running the program:
```r
install.packages("pixmap")
install.packages("bmp")
install.packages("devtools")
library(pixmap)
library(bmp)
library(devtools)
```

## The Process
1. **Image Decomposition**: Decomposes the image matrix using singular values.  
2. **Compression**: Reconstructs the image using the top 30 singular values to reduce file size while maintaining quality.  
3. **Comparison**: Provides a report on the reduction in pixel count and file size.  

---
