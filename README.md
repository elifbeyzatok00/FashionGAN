# Fashion MNIST Generative Adversarial Network (GAN) with Keras

## Overview

This repository contains code to train and evaluate a Generative Adversarial Network (GAN) on the Fashion MNIST dataset using Keras and TensorFlow. The GAN consists of a generator and a discriminator network trained adversarially to generate realistic fashion item images.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Training the GAN

1. Run the training script:

   ```bash
   python train_gan.py
   ```

   - Adjust parameters such as number of epochs, batch size, and latent dimension as needed.

2. Monitor training progress and generated images.

### Generating Images

1. After training, generate new images with a pretrained model:

   ```bash
   python generate_images.py --model <path-to-model>
   ```

   - Replace `<path-to-model>` with the path to a saved model.

2. View and save the generated images.

## Credits

- Adapted from [Keras GAN tutorial](https://keras.io/examples/generative/dcgan_overriding_train_step/).
- Fashion MNIST dataset provided by Keras.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
