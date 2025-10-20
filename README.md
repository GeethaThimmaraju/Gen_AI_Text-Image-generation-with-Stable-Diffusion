🎨 #Text-to-Image Generator using Stable Diffusion

Turn any text prompt into stunning images in seconds! This project uses Stable Diffusion to generate images from text prompts with a simple web-based interface built using Gradio.

🔥 Features

Generate images from any text prompt

Choose different styles for your images (Realistic, Cartoon, etc.)

Specify the number of images to generate

Fast and interactive frontend using Gradio

💻 Requirements

Python 3.10+

NVIDIA GPU recommended for fast image generation

Running on CPU is possible, but it will be very slow

Internet connection (to download pretrained models)


#Install dependencies:

pip install --upgrade pip
pip install diffusers transformers accelerate pillow torch torchvision torchaudio gradio -q

🚀 #Usage

Run the app:

python app.py


Open the Gradio interface in your browser

Enter a text prompt, choose style and number of images, then click Generate

⚡ Example

Prompt: A cat wearing sunglasses on the beach
Style: Realistic
Number of Images: 1

The app generates the image in seconds (faster on GPU).

💡 #Notes

GPU is highly recommended for fast generation

You can experiment with different prompts and styles

Make sure you have enough RAM and storage for model weights

