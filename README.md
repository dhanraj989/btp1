# BTP1
## Image denoising of handwritten Devanagari script images
Objective: The primary aim of this research is to develop and evaluate image-denoising algorithms that can effectively reduce noise in handwritten Devanagari script images.  
• Created a dataset utilizing the images from the IIIT-HW-Dev Dataset as ground truth images and generated corresponding noise images by adding Gaussian, Salt and Pepper, Poisson, and Speckle noises randomly.  
• Trained the Encoder-Decoder, Pyramid Real Image Denoising Network (PRIDNet), Real Image Denoising Network (RIDNet), Boosted Residual Dense UNet, Pix2Pix Generative Adversarial Network(Pix2Pix GAN) models on a smaller dataset made by combining training examples from two datasets, SIDD and RENOIR.  
• Took two architectures that performed well on the smaller dataset and fine-tuned them on the Devanagari script dataset, and trained both architectures from scratch on the Devanagari script dataset created.  
• Obtained a Peak Signal to Noise Ratio (PSNR) of about 38dB for the best architecture on the Devanagari script dataset created.
