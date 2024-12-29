[Solution link ](https://drive.google.com/drive/folders/1nqx-ER8bs95yp_Zrdi8xztMX0wTJmJId)


# Introduction
Image denoising is an important task in computer vision. It helps to remove unwanted noise from images while keeping important details and edges. Noise in images can happen due to bad lighting, camera problems, or issues during image transfer. This makes images harder to use for tasks like finding edges, recognizing objects, or analyzing the content.

This project looks at how different filters can reduce noise in images. It focuses on simple filters, like Box, Gaussian, and Median filters, which are easy to use but may not handle all cases well. It also studies advanced filters, like Adaptive and Bilateral filters, which give better results but take more time to process.

The project measures how well these filters perform with different levels of noise and sizes of filter windows (kernels). It uses numbers like Mean Squared Error (MSE) and Peak Signal-to-Noise Ratio (PSNR) to compare them. The study also checks how the filter size affects noise removal, keeping edges, and the time it takes to process images. The goal is to find the best way to use these filters in real situations, balancing between quality and speed.

set of three grayscale images was used as input for applying different types of noise, with each noise type added at varying intensity levels.
