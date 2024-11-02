# EdgeDetection
This mini-project aimed at becoming familiar with the practical use of some edge detecting filters.
The provided notebook has two main sections.
**Section A:**
In this section, sobel filter is applied on two different images to detect all edges.
Then, unsharp masking using laplacian filters is applied on two other images to enhance the details of the image and make the edges more defined.
Next, I used two different methods for automating the thresholding phase of canny edge detection: 1- Otsu's thresholding, which computes the suitable thresholds automatically and seperates background from foreground. 2- Adaptive thresholding:
This method computes local thresholds based on a small region of the image, it's specifically useful when the picture we're working with was not taken in an even lighting condition.
**Section B:**
At first, gaussian filter was applied to the image to get rid of any unwanted noise, and two different lapalcian filters were used for detecting the lines in the image.
