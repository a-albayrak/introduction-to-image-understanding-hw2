# Introduction to Image Understanding Homework 2: Salt and Pepper Noise, Robert's filter, Canny Edge Detector

## Overview

1. Upload a personal image in a hosting place that can be accessed using an URL. Alternatively, you can pick an image from an URL already available (but not the ones used in the lecture).
2. Convert your image into grayscale (you can use any library for this).
3. Add salt and pepper noise with a probability of 0.25. That is to say 25% of pixels are affected by the noise (you can use any library for this).
4. Perform median filtering with at least 3 different kernel sizes (you can use any library for this) on the noisy image. Compare the results by displaying images. Comment on the results, which size is better.
5. Take the original image (Step 2). Implement Robert's filters by yourself:
Show the results of these filters. What kind of edges these filter detected?
6. Take the original image (Step 2). Use Canny Edge Detector incorporated in OpenCV. Pick two different sets of hysteresis thresholds. What can you tell about the effect on the obtained edges? Write your comments.
