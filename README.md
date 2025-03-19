# 📌 Image Denoising Using Genetic Algorithm

This repository explores enhancing image denoising by optimizing a Gaussian filter using a Genetic Algorithm (GA).

# 📜 Overview

This project applies artificial noise to images and then attempts to denoise them using an optimized Gaussian filter, where the kernel size and sigma value are tuned using a Genetic Algorithm.

# 🛠️ Processing Pipeline

- Input Image (Original) → Stored in the "sharp" folder.
- Noise Injection → Apply Gaussian noise, save noisy images in the "noise" folder.
- Genetic Algorithm Optimization → Find the best combination of kernel size and sigma for the Gaussian filter.
- Denoising → Apply the optimized Gaussian filter, save the output in the "result" folder.
- Comparison & Evaluation → Compare the original, noisy, and denoised images.

# 📂 Folder Structure

📂 Image-denoise-project  
│── 📁 sharp      -> Original (clean) images  
│── 📁 noise      -> Noisy images (after applying Gaussian noise)  
│── 📁 result     -> Denoised images (after applying optimized Gaussian filter)  
│── 📜 main.ipynb -> Main notebook for all tasks  
│── 📜 README.md  -> Documentation

# 🔧 Requirements

Install dependencies before running the code:

```bash
pip install numpy opencv-python scikit-image scipy
```

# 📊 Results & Evaluation

The original, noisy, and denoised images are stored for comparison.  
You can evaluate image quality improvements using PSNR, SSIM, or MSE.

# 📌 Future Improvements

Test with other noise types (Poisson, Salt & Pepper).  
Optimize denoising with Deep Learning methods.  
Automate parameter tuning for faster convergence.

# 🎯 Contributors

Vo Nguyen Phat - Developer.  
I am learning day by day. Feel free to contribute by submitting issues or pulling requests.
