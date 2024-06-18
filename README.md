---

# Image Denoising using Multi-level Wavelet-CNN (MWCNN)

## Overview

This project implements an image denoising solution based on the Multi-level Wavelet Convolutional Neural Network (MWCNN) architecture. MWCNN combines wavelet transforms with convolutional neural networks to effectively remove noise from images while preserving important details.

## Model Architecture

The MWCNN architecture consists of multiple convolutional blocks interspersed with wavelet downsampling and upsampling layers. Key features include:
- **Wavelet Transform:** Used for multi-level decomposition and reconstruction of image details.
- **Convolutional Blocks:** Employed for feature extraction and spatial information processing.
- **Batch Normalization:** Enhances training stability and accelerates convergence.
- **Loss Function:** Mean Squared Error (MSE) is minimized during training.
- **Optimizer:** Adam optimizer with a learning rate of 0.0009.

## Performance

The model achieved a mean Peak Signal-to-Noise Ratio (PSNR) of 30.45 dB on the test dataset, indicating high image quality restoration.

## Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-denoising-mwcnn.git
   cd image-denoising-mwcnn
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Notebooks

To run the notebooks:
- Ensure Jupyter Notebook is installed (`pip install notebook`).
- Launch Jupyter Notebook server:
  ```bash
  jupyter notebook
  ```
- Open and execute each notebook in the order of their numerical prefixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

- Multi-level Wavelet-CNN for Image Restoration Research Paper: [Link](https://arxiv.org/abs/1805.07071)

---
