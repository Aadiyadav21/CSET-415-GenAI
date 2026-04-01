# 🚀 Generative AI Lab Experiments
### 📘 Course: CSET419 – Introduction to Generative AI  

This repository contains a collection of **hands-on lab experiments** covering core concepts in **Generative AI**, including GANs, VAEs, Transformers, CNNs, and Style Transfer.

Each lab focuses on building practical intuition by implementing models and analyzing their outputs.

---

## 📌 Table of Contents
- Lab 1: Medical Image Generation (Stable Diffusion)  
- Lab 2: GAN for Image Generation  
- Lab 3: Variational Autoencoder (VAE)  
- Lab 4: Text Generation (LSTM & Transformer)  
- Lab 5: Image-to-Image Translation (CNN)  
- Lab 6: Pix2Pix GAN  
- Lab 7: Neural Style Transfer  
- Lab 8: Artistic Image Generation (DCGAN)  
- Lab 9: Sequence Generation  

---

# 🧪 Lab 1 – Medical Image Generation  

## 🎯 Objective  
To understand how pre-trained generative models can create synthetic medical images.

## 🧠 Key Concept  
Using **Stable Diffusion** to generate realistic X-ray images from text prompts.

## ⚙️ Workflow  
- Load pre-trained model  
- Input medical prompts  
- Generate X-ray images  
- Save dataset in structured format  

## 📊 Output  
- Synthetic X-ray dataset  
- Organized folders  
- Visual verification samples  

## 💡 Insight  
Useful for **data augmentation** and **privacy-sensitive domains like healthcare**.

---

# 🧪 Lab 2 – GAN for Image Generation  

## 🎯 Objective  
To train a GAN model to generate handwritten digits.

## 🧠 Key Concept  
Two networks compete:
- **Generator** → creates fake images  
- **Discriminator** → detects real vs fake  

## ⚙️ Workflow  
- Load MNIST dataset  
- Train Generator & Discriminator  
- Monitor loss & accuracy  
- Generate samples during training  

## 📊 Output  
- Generated digit images  
- Training logs  

## 💡 Insight  
GANs can **learn complex data distributions without labels**.

---

# 🧪 Lab 3 – Variational Autoencoder (VAE)  

## 🎯 Objective  
To learn latent representations and generate new data samples.

## 🧠 Key Concept  
- Encoder → compresses input  
- Decoder → reconstructs data  
- Learns **probabilistic latent space**

## ⚙️ Workflow  
- Train on Fashion-MNIST  
- Use reparameterization trick  
- Optimize reconstruction + KL loss  

## 📊 Output  
- Reconstructed images  
- New generated samples  
- Latent space visualization  

## 💡 Insight  
VAEs generate **smooth and diverse variations** of data.

---

# 🧪 Lab 4 – Text Generation Models  

## 🎯 Objective  
To generate text using deep learning models.

## 🧠 Models  
- LSTM (sequential learning)  
- Transformer (attention-based learning)

## ⚙️ Workflow  
- Text preprocessing  
- Tokenization  
- Model training  
- Text generation using seed input  

## 📊 Output  
- Generated text sequences  

## 💡 Insight  
Transformers outperform LSTMs due to **parallel processing & attention**.

---

# 🧪 Lab 5 – Image-to-Image Translation (CNN)  

## 🎯 Objective  
To implement a baseline encoder-decoder model.

## 🧠 Key Concept  
Translate images using **pixel-wise loss (MSE/L1)**.

## ⚙️ Workflow  
- Prepare paired dataset  
- Train encoder-decoder CNN  
- Generate translated images  

## 📊 Output  
- Translated images  
- Loss plots  

## ⚠️ Limitation  
Outputs are **blurry** due to lack of adversarial learning.

---

# 🧪 Lab 6 – Pix2Pix GAN  

## 🎯 Objective  
To improve image translation using GAN.

## 🧠 Key Concept  
- Generator: U-Net  
- Discriminator: PatchGAN  
- Uses **Adversarial + L1 Loss**

## ⚙️ Workflow  
- Train GAN on paired images  
- Compare with CNN results  

## 📊 Output  
- Sharper, realistic images  

## 💡 Insight  
GANs produce **high-quality outputs compared to CNNs**.

---

# 🧪 Lab 7 – Neural Style Transfer  

## 🎯 Objective  
To combine content and artistic style of images.

## 🧠 Model  
Pre-trained CNN (VGG19)

## ⚙️ Workflow  
- Extract content + style features  
- Compute losses  
- Optimize generated image  

## 📊 Output  
- Stylized images  

## 💡 Insight  
Deep networks can **separate structure and texture**.

---

# 🧪 Lab 8 – Artistic Image Generation (DCGAN)  

## 🎯 Objective  
To generate creative images using GAN.

## 🧠 Key Concept  
- Generator creates images from noise  
- Discriminator evaluates realism  

## ⚙️ Workflow  
- Train DCGAN  
- Explore latent space  
- Generate samples  

## 📊 Output  
- Artistic generated images  

## 💡 Insight  
GANs can produce **creative and novel outputs**.

---

# 🧪 Lab 9 – Sequence Generation  

## 🎯 Objective  
To generate text sequences using neural networks.

## 🧠 Models  
- LSTM  
- Transformer  

## ⚙️ Workflow  
- Prepare text dataset  
- Train models  
- Generate sequences  

## 📊 Output  
- Generated text  

## 💡 Insight  
Transformers provide **better context understanding**.

---

# 🛠️ Tech Stack  

- **Languages:** Python  
- **Frameworks:** PyTorch, TensorFlow/Keras  
- **Tools:** Google Colab  
- **Libraries:** NumPy, Matplotlib, Hugging Face Diffusers  

---

# 📈 Key Learnings  

✔ Understanding of core Generative AI models  
✔ Hands-on experience with GANs, VAEs, Transformers  
✔ Difference between reconstruction vs adversarial learning  
✔ Importance of latent space in generative models  
✔ Practical implementation of real-world AI systems  

---

# 🌟 Future Improvements  

- Add diffusion models (advanced)  
- Train on custom datasets  
- Improve model performance  
- Deploy models as web apps  

---

# 📌 How to Run  

```bash
# Clone the repo
git clone https://github.com/your-username/generative-ai-labs

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook
```

---

# 🤝 Contribution  

Feel free to fork, improve, and contribute to this repository.

---

# 📜 License  

This project is for academic and educational purposes.

