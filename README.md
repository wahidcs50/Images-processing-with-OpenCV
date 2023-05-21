# Images-processing with OpenCV
This repository focuses on utilizing OpenCV, a popular open-source computer vision library, for various image processing tasks. OpenCV provides a wide range of functions and algorithms specifically designed for image processing, making it a powerful tool for developing image processing applications such as object detection, image smoothing image segmentation and more.
# contents
1 Image processing for Edge detection
2 Image processing for Edge detection
This technique segments the input image into different regions based on color, texture, or other visual characteristics.
# Before and after examples:
![My Image](g.PNG)
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
# Image processing with frequency domain filters

Image processing in the frequency domain involves transforming an image from the spatial domain to the frequency domain using techniques such as the Fast Fourier Transform (FFT). Frequency domain filters such as ideal filter, betterworth filter, and gaussian filters with high pass and low pass frequencies can then be applied to the transformed image to achieve desired effects such as noise removal, sharpening, or blurring.

This repository provides implementation of high pass and low pass filters, which are commonly used in frequency domain filtering. High pass filters allow for preserving and enhancing high-frequency components, while low pass filters enable smoothing and preserving low-frequency information in an image.
# Ideal low pass filter
![IFlp](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/bc8d1487-b2ce-4cd7-97e5-9ea22b91e26c)
# Ideal high pass filter
![ifhp](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/d0f07055-a013-49de-bdec-ffb2e39655f7)
# Betterworth low pass filter
![Bwlp](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/f6c73b3e-8dff-4e6a-997b-c39a581d17f3)

# Betterworth high pass filter
![BWhp](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/4550a660-25a6-4d25-8b56-e8b66e84fb2a)

# Gussian low pass filter
![GLp](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/f4cf3b1a-8f97-4a7e-abb4-5f8d3013f46c)

# Gussian high pass filter
![ghp1](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/622c151a-4bbb-4abc-adf5-febd90fa93bb)
![Ghpf2](https://github.com/monly98/Images-processing-with-OpenCV/assets/93678291/0f530c14-5d0a-4218-809c-b2aa5a26d70b)

# Morphological image processing with opening-and-closing
Opening and closing operations are fundamental techniques in morphological image processing. They are used to improve image quality, remove noise, and modify the shape and connectivity of objects in an image.

Opening is a two-step operation that involves applying an erosion operation followed by a dilation operation. It is useful for removing small objects, thin lines, and noise from an image while preserving the larger structures.

Closing, on the other hand, is the reverse of opening. It consists of a dilation operation followed by an erosion operation. Closing is effective for filling small holes, joining broken structures, and smoothing the boundaries of objects.

This repository provides implementation of opening and closing operations, allowing you to apply these morphological operations to your images.
