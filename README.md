# CarND-LaneLines-P1
Detect Lane Lines
My pipeline consisted of 5 steps.
# 1 GrayScale
First, I converted the images to grayscale, then I used Gaussian blur to blur the image. After Gaussian blur, I apply canny function to the image to display only the edges where color changes drastically.
Gaussian blur and canny parameters are shown below:
Kernel size = 5
Low_threshold = 50
High_threshold = 150
