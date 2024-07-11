# image-repair-and-restoration
A deep learning approach to image reconstruction and restoration using autoencoders

This project leverages deep learning to tackle image repair and restoration. It implements three advanced autoencoder architectures: Convolutional Autoencoder, Self-Attention Autoencoder, and Multi-Head Attention Autoencoder. Each model is designed to restore high-quality images from degraded ones. Evaluations using SSIM and PSNR metrics show that the Multi-Head Attention Autoencoder excels in image denoising and restoration, achieving the highest performance.


## Dataset

The dataset used for training and testing the models is the [Fer2013](https://www.kaggle.com/datasets/msambare/fer2013) dataset.
It consists of 35,000 images of different facial expressions. The data includes 48x48 pixel grayscale images of faces. 


## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
