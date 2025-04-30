# GAN Demo on MNIST

This project is a lightweight implementation of a Generative Adversarial Network (GAN) trained on the MNIST dataset, designed for quick demonstration and educational purposes. It is ideal for use in live presentations or introductory machine learning seminars.

## 📁 Files
- `Lightweight_GAN_MNIST_Demo.ipynb`: Colab-compatible notebook containing the GAN implementation and training loop.
- `gan_colab_qr.png`: QR code linking directly to the Colab notebook for easy access during presentations.

## 🚀 Features
- Simple generator and discriminator architectures  
- Minimal dependencies (uses PyTorch and torchvision)  
- Fast training (~5 epochs for demo)  
- Generates 16 sample MNIST digits at the end of training

## 🧠 How It Works
1. The **Generator** creates fake MNIST digits from random noise.  
2. The **Discriminator** tries to distinguish between real and fake images.  
3. Both networks are trained in a competitive loop to improve performance.

## 🖥️ Usage
1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Run all cells. Training takes a few minutes on GPU.
3. Generated images are visualized at the end of the notebook.

## 🧾 Requirements
- Python 3.x  
- PyTorch  
- torchvision  
- matplotlib  

These are pre-installed in Colab, so no setup is needed if you're using that platform.

## 📌 Notes
- This model is intentionally lightweight for speed.  
- For higher-quality results, increase the number of epochs or use deeper models.  
- Perfect for classroom demos or slideshows where time and performance are limited.

## 🔗 Quick Access
Scan the `gan_colab_qr.png` to open the notebook directly in your browser.

## 📜 License
For educational and non-commercial use only.

---

Created for a Machine Learning seminar on Generative Adversarial Networks (GANs).
