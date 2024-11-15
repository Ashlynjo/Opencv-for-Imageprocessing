# OpenCV-for-Image Processing

In this repository, I will be including codes that I have written to aid in image processing. Image processing is an essential tool for researchers working in fields that require critical analysis of images for research data. For instance, I had to analyze my particle data to track their movement, and doing it manually is tedious due to the large number of particles and images per second (frames), which could be 30 per second or more.

Each cell contains code labeled with its function, such as "image reading," which displays the image whose file path you have specified in the designated place. I have also included key comments with instructions on how to change parameters. For example, you need to change the kernel number only to an odd number.

The topics for which I have written code include:
- Image Reading
- Video Reading
- Grayscale Conversion
- Gaussian Blur
- Edge Display
- Finding Edges of a Blurred Image (Helpful to avoid unnecessary borders)
- Dilating the Borders
- Restoring the Original Image from the Dilated (Eroded) One
- Resizing an Image
- Contour Detection (Only works if the image is in edge scale; gives only the number of contours)
- Finding the RGB Values of an Image
- Thresholding an Image (Binarization)
- Drawing a Blank Image of the Same Dimensions
- Drawing Contours
- Drawing Contours with Threshold
- Drawing Contours Using a Blurred Image
- Color Operations: In Matplotlib, images are in BGR format, while actual images are in RGB. We can have RGB, BGR, HSV, LAB.
- Displaying Images in Matplotlib (Note: images in OpenCV are in BGR)
- Converting to RGB
- Finding the Separate R, G, B Values on an Image (Black & White)
- Creating RGB Images: Create a Blank Image and Merge It with the Colors
- Bitwise Operations: Drawing Rectangles, Circles
- Bitwise AND, OR, XOR – Shows Non-Intersection Parts
- Masking: Using Bitwise Operators, you can use OR, AND to create different shapes and then use them as a mask
- Computing Histogram for Grayscale Images
- Computing Histogram for Masked Grayscale Images
- Histogram for Colored Images
- Thresholding: Simple, Inverse, and Adaptive
- Laplacian, SobelX, SobelY Edge Detection
