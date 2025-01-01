# Audio-Noise-Reduction-Techniques-Analysis-and-Comparison
This repository contains the implementation and analysis of three distinct audio noise reduction techniques—**Wiener Filter**, **Bandpass Filter**, and **Autoencoder**—for white noise denoising in audio signals. The project evaluates the performance of these algorithms in terms of **Signal-to-Noise Ratio (SNR)**, **Mean Squared Error (MSE)**, and **Peak Signal-to-Noise Ratio (PSNR)**.

## Overview

Audio signals are inherently sensitive and complex, often marred by background noise, which impacts their clarity and usability. This project aims to address the challenges posed by white noise by:
* Implementing three noise reduction algorithms.
* Comparing their effectiveness using quantitative metrics.
* Visualizing results using spectrograms and performance graphs.

## Key Features

### 1) Algorithms Implemented:

* **Wiener Filter:** A linear filter that minimizes the mean square error for stationary signals.
* **Bandpass Filter:** Filters out frequencies outside a specified range using a Butterworth filter.
* **Autoencoder:** A neural network-based approach leveraging convolutional layers for dynamic noise reduction.

### 2) Performance Metrics:

* SNR, MSE, and PSNR calculations for evaluating denoising efficiency.
* Comprehensive comparison across methods.

### 3) Visualizations:

* Spectrograms of clean, noisy, and filtered audio signals.
* Bar graphs depicting comparative performance.

## Results

The analysis indicates that the Autoencoder outperforms other methods, achieving higher SNR and PSNR values while maintaining lower MSE. This highlights its adaptability and effectiveness for audio noise reduction tasks.
