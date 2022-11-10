# 4 Biomedical Image Denoising Using CBDNet and UNet

​Image denoising works are mostly inclined towards general images and not biomedical images.

​Newer algorithms are mostly implemented for general images.

​Current algorithms being used for biomedical image denoising are computationally expensive.

​So in this work we have used UNet Algorithm and CBDNet Algorithm for two biomedical image datasets and compared it's denoising performance and computation time by using certain metrics.


# Workflow:

Step 1: Downloading 2 Datasets

Step 2: Inducing Noise in Clean Images of varying intensities 3%,5% and 9% (Rcian Noise for 1st Dataset and Poisson Noise for 2nd Dataset) and resizing image to similar image.

Step 3: Denoising Image using two algorithms CBDNet and UNet.

Step 4: Measuring the Image quality metrics like PSNR,SSIM etc .

Step 5: Then comparing the results

# Outcome of the Work

The key outcome is both algorithms works well for biomedical image denoising.​

Computation Time of UNET is less compared to CBDNET.​

More the number of Epochs greater are the results.​

PSNR and SSIM improved after denoising, thus retaining the originality of Image. 

Thus, the image should be less corrupted by noise to get better results.
