# Images-processing with OpenCV
This repository focuses on utilizing OpenCV, a popular open-source computer vision library, for various image processing tasks. OpenCV provides a wide range of functions and algorithms specifically designed for image processing, making it a powerful tool for developing image processing applications such as object detection, image smoothing image segmentation and more.
# contents
1 Image processing for Edge detection
2 Image processing for Edge detection
This technique segments the input image into different regions based on color, texture, or other visual characteristics.
# Before and after examples:
# Befor
![My Image](g.PNG)
# After
![My Image](gg.PNG)
# Image processing for Edge detection
This technique detects and highlights objects of interest in the input image using diferent filters for example Laplacian, Sobel, Cany Filter and prewitt.
# Before and after examples
![Detection](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/210b7bb1-fe2b-4bc4-b156-b830980f06f1)
# Image processing with Smoothing filters
Image filters play a vital role in various image processing tasks, such as noise reduction, feature enhancement, and image restoration. This repository provides efficient implementations of popular filters that can be easily integrated into your own projects.
# Filters
# Average Filter
The average filter is a simple and effective technique used in image processing to reduce noise and blur images. It works by replacing each pixel's value with the average of its neighboring pixels, typically within a square or rectangular window.
The average filter is widely used because of its simplicity and ability to preserve the overall image structure while reducing high-frequency noise. It is especially useful for smoothing images and preparing them for further analysis or visualization.
![sm1](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/29906b80-dcbe-4d9c-9dde-60a4b011a602)

# Median Filter
The median filter is a nonlinear filter that replaces each pixel in an image with the median value of its neighboring pixels. It is effective in reducing impulse noise or salt-and-pepper noise, preserving edges, and preserving fine details.
![median](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/f5237fd2-297b-4f74-82bc-fa529c3df142)


# Minimum Filter
The minimum filter, also known as erosion, replaces each pixel in an image with the minimum value of its neighboring pixels. It can be used for noise reduction, edge detection, and morphological operations.

# Maximum Filter
The maximum filter, also known as dilation, replaces each pixel in an image with the maximum value of its neighboring pixels. It can be used for noise reduction, edge detection, and morphological operations.
![minmax](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/f8d92fdc-251c-4b90-9d5b-2b9dff85fdf7)

# Histogram Equalization
Histogram equalization is a technique used to enhance the contrast and improve the overall appearance of an image. It redistributes the pixel intensities in an image to achieve a more balanced histogram, resulting in improved visual quality.
![equ](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/3bc05318-64e5-4143-b077-40323f9a0b04)

