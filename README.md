# Image Generation with Pre-trained Models
This repository contains a Python implementation for generating high-quality images from text prompts using Stable Diffusion XL. This project demonstrates the power of Latent Diffusion Models (LDMs) in creative AI workflows.

---

# 🚀 How to Use
Simply run the main generation script:

Bash
python generate_images.py

# ⚙️ Customization Parameters
In generate_images.py, you can modify these key variables:
- prompt: Your creative text description.
- num_inference_steps: Higher values (e.g., 50) increase detail but take longer; lower values (e.g., 20) are faster.
- guidance_scale: Higher values make the model stick closer to the text prompt.

# 🧠 How it Works
Stable Diffusion generates images through a denoising process. It starts with a canvas of pure Gaussian noise and, guided by the text prompt's embeddings, gradually "sculpts" the noise into a coherent image over several steps.


# 📂 Project Structure
1. generate_images.py: The core generation script.

2. outputs/: Folder where generated images are stored.

3. requirements.txt: List of necessary Python libraries.

---

# Author
- Name: Pruonh Kimliya
- Email: kimliyapruonh@gmail.com

