# GAN-Image-Transformation

## Overview
This project implements multiple Generative Adversarial Networks (GANs) for image transformation tasks. It focuses on:
- **CGAN**: Transforming any facial expression into a smiling face.
- **DCGAN**: Generating high-resolution images from scratch.
- **BigGAN & StyleGAN3** (Pre-trained Models): Enhancing image generation quality.

## Features
- **Conditional GAN (CGAN)** for facial emotion transformation.
- **Deep Convolutional GAN (DCGAN)** for high-resolution image synthesis.
- **Implementation of advanced GAN training techniques**: Curriculum learning, Two Time-Scale Update Rule (TTUR), gradient penalty.
- **Evaluation Metrics**: Inception Score (IS), Fréchet Inception Distance (FID).
- **Pretrained models & Residual Pathways** for enhanced output quality.

## Repository Structure
```bash
GAN-Image-Transformation/
│── datasets/                    # Store datasets or dataset loading scripts
│   ├── facial_emotion/           # Facial Emotion Recognition Dataset
│   ├── high_res_images/          # High-quality dataset for DCGAN
│── models/                      # Trained models (checkpoints)
│── src/                         # Source code for different GAN implementations
│   ├── cgan/                     # Conditional GAN for facial expression transformation
│   ├── dcgan/                     # Deep Convolutional GAN for high-resolution images
│   ├── utils.py                  # Helper functions
│── evaluation/                   # Model evaluation scripts (IS, FID, etc.)
│── results/                      # Generated images & logs
│── notebooks/                    # Jupyter notebooks for experiments
│── scripts/                      # Training and inference scripts
│── README.md                     # Project documentation
│── requirements.txt               # Dependencies
│── .gitignore                     # Files to ignore in Git
```

## Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/deephabiswashi/GAN-Image-Transformation.git
   cd GAN-Image-Transformation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run training:
   ```bash
   python scripts/train_cgan.py  # For CGAN
   python scripts/train_dcgan.py  # For DCGAN
   ```

## Usage
- **Upload an image** to transform a facial expression into a smiling face.
- **Generate high-quality images** using the trained DCGAN model.
- **Evaluate performance** with IS and FID scores.

## HTML & CSS Formatting (Minimal Styling)
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; }
        h1 { text-align: center; color: #333; }
        pre { background: #f4f4f4; padding: 10px; border-radius: 5px; }
    </style>
</head>
<body>
    <h1>GAN Image Transformation</h1>
    <p>Transforming facial expressions and generating high-resolution images using GANs.</p>
    <pre>
        git clone https://github.com/deephabiswashi/GAN-Image-Transformation.git
        cd GAN-Image-Transformation
    </pre>
</body>
</html>
```

## Contributors
- **Deep Habiswashi(2230167)** - Developer
- **Avilasha Goswami(2230162)** - Developer
- **Soumyadeep Dutta(2230207)** - Developer
- **Sudeshna Mohanty(2230211)** - Developer

## License
This project is licensed under the MIT License.

