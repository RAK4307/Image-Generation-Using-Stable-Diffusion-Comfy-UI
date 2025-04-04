# 🖼️ Image Generation using Stable Diffusion - Comfy UI ✨
Welcome to the Stable Diffusion Comfy UI project! This repository integrates the power of the Stable Diffusion model with the user-friendly Comfy UI interface, allowing you to generate stunning images from text prompts with ease. 🌟

## 🚀 Table of Contents 

Overview

Features

Installation

Usage

Configuration

Contributing

License

## Overview 🖼️
Stable Diffusion is a cutting-edge AI model capable of generating high-quality images from text descriptions. This project uses Comfy UI, a sleek and simple interface, to interact with the Stable Diffusion model. Whether you're an artist, developer, or AI enthusiast, this tool gives you the power to create beautiful images with just a few lines of text! 

## ✨ Features ✨
Text-to-Image Generation: Transform your descriptions into beautiful, high-quality images.

Intuitive User Interface: A simple and elegant Comfy UI for seamless use.

Customizable Parameters: Fine-tune style, resolution, and creativity.

Batch Generation: Create multiple images in a single go.

GPU Acceleration: Harness your local GPU to speed up image creation.

## 🛠️ Installation 🛠️
Ready to get started? Follow these simple steps to set up Stable Diffusion Comfy UI on your machine!

#### Requirements
Python 3.8+ 

CUDA (for GPU acceleration, optional but recommended) 

Git (to clone the repository) 

#### Steps :-

Clone the Repository:

First, clone the repository by running the following command:

    git clone https://github.com/your-username/stable-diffusion-comfy-ui.git

    cd stable-diffusion-comfy-ui

#### Install Dependencies:

Create a virtual environment (recommended) and install the required packages:

    python -m venv venv

    source venv/bin/activate    # On Windows: venv\Scripts\activate

    pip install -r requirements.txt

#### Download the Stable Diffusion Model:

Download the pretrained Stable Diffusion model from Hugging Face or CompVis. Once downloaded, place the model files in the models/ directory.

Run the Application:

    python app.py

Your Comfy UI will be available in your browser at `http://127.0.0.1:5000.` 🎉

## Usage✨
#### Generating Images

Enter a Prompt: Type your desired description (e.g., "A peaceful sunset over the ocean") 🌅.

Adjust Parameters: Fine-tune options like resolution, creativity, and style 🛠️.

Generate Image: Click the `Generate` button and let the magic happen! 🪄

Save the Image: Once you're happy with the result, click `Save` to download your masterpiece! 💾

#### Example Prompt :-
To generate a futuristic city image, you might try:

1 . "A magical forest with bioluminescent trees and a small river."

![Screenshot 2025-02-07 155729](https://github.com/user-attachments/assets/9f941ce1-8f3c-46c7-9f99-7f266d2d381e)

2 . " An astronaut exploring a mysterious alien planet with glowing plants."

![Screenshot 2025-02-07 162225](https://github.com/user-attachments/assets/af3aee6b-9e2d-4071-8143-9263635d5353)



## 📂 Configuration
You can customize your experience by adjusting the `config.py` file.

Here are some important parameters:

MODEL_PATH: The path to the Stable Diffusion model.

OUTPUT_PATH: Where your generated images are saved.

DEFAULT_RESOLUTION: Default resolution of generated images (e.g., 512x512).

INFERENCE_STEPS: Higher steps improve image quality.

GUIDANCE_SCALE: Controls how closely the model follows your prompt (higher = more detail).


## 📝 Contributing

We love contributions! If you have ideas, fixes, or enhancements, we welcome you to submit a pull request.

## 📜 License 📜
This project is licensed under the  `MIT License`.
