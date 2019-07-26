# Finding Lane Lines on the Road

Pipeline:

1. Convert the input image into grayscale.
2. Perform a Gaussian blur on the grayscale image to reduce image noise and reduce detail.
3. Convert the output image in step 2 into edges by using [Canny edge detection](https://en.wikipedia.org/wiki/Canny_edge_detector).
4. Define a mask to cover only where the lane lines are.
5. Highlight the lane lines by drawing red lines on the masked blank image.
6. Get the output image with lines drawn on the original image.

