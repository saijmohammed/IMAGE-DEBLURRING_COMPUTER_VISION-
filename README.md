# 🔍 Image Deblurring using Wiener Filter
## Computer Vision Project

---

## 📌 Project Overview
This project focuses on restoring blurred images using classical **image processing techniques**.  
We simulate motion blur and noise, then apply **Wiener deconvolution** to recover the original image.

The goal is to understand how image degradation works and how to reverse it using frequency-domain methods.

---

## 🎯 Objectives
- Simulate motion blur on images
- Add Gaussian noise
- Apply Wiener filter for image restoration
- Evaluate performance using PSNR (Peak Signal-to-Noise Ratio)

---

## 🧠 Techniques Used
- Fourier Transform (FFT)
- Motion Blur Modeling (PSF)
- Wiener Deconvolution
- Noise Modeling
- Image Quality Evaluation (PSNR)

---

## 🛠️ Technologies
- Python 🐍
- NumPy
- OpenCV
- Matplotlib
- SciPy

---

## ⚙️ How It Works

### 1️⃣ Blur Simulation
We generate a **Point Spread Function (PSF)** to simulate motion blur.

### 2️⃣ Add Noise
Gaussian noise is added to simulate real-world conditions.

### 3️⃣ Frequency Domain Processing
The image is transformed using FFT.

### 4️⃣ Wiener Filter
We apply Wiener deconvolution to restore the image.

---

## 📊 Evaluation Metric

We use:

- **PSNR (Peak Signal-to-Noise Ratio)**  
Higher PSNR = Better restoration quality

---

## 📄 Report
--> https://docs.google.com/viewer?url=https://raw.githubusercontent.com/saijmohammed/IMAGE-DEBLURRING_COMPUTER_VISION-/main/Complete_Deblurring_Report.pdf

