# ghibli-lora-generator
# Ghibli Style Transfer with LoRA 🎨

Convert real-world photos into beautiful Studio Ghibli-inspired art using lightweight LoRA fine-tuning on Stable Diffusion.

## Project Overview

This project demonstrates an efficient style transfer pipeline where input photographs are transformed into Ghibli-style images. The model was fine-tuned using the [LoRA](https://arxiv.org/abs/2106.09685) (Low-Rank Adaptation) method on top of the `runwayml/stable-diffusion-v1-5` base model.

<p align="center">
  <img src="examples/photo_input.jpg" width="45%" />
  <img src="examples/ghibli_output.jpg" width="45%" />
</p>

---

## 🚀 Features

- **Photo-to-Ghibli**: Stylizes any input photo into a soft, dreamlike Ghibli aesthetic
- **LoRA Training**: Lightweight training (~100MB) instead of full model fine-tuning
- **Built on Stable Diffusion v1.5**
- Supports inference using HuggingFace `diffusers` or AUTOMATIC1111 Web UI
- Easy to adapt to other styles (just swap dataset)

---

## 📁 Project Structure


