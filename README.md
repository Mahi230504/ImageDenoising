#Image Denoising with OpenCV

This project demonstrates how to perform image denoising using the Non-Local Means (NLM) algorithm provided by OpenCV. The script removes noise from a noisy image while preserving the details and structure of the image.

## Features
- Denoises color images using the Non-Local Means algorithm.
- Customizable parameters for tuning the denoising process.


## Installation
1. Clone the repository or download the script:
   ```bash
   git clone https://github.com/Mahi230504/ImageDenoising.git
   cd image-denoising

Parameters

You can customize the denoising process by changing the following parameters:

h: Controls the filtering strength for the luminance channel. Higher values remove more noise but may blur details.
hColor: Controls the filtering strength for the color channels.
templateWindowSize: Size of the template patch (default: 7).
searchWindowSize: Size of the search window (default: 21).
