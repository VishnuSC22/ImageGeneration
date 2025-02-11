# Image Generation using Stable Diffusion and ComfyUI

## Overview
This project utilizes **Stable Diffusion** with **ComfyUI** to generate high-quality AI-generated images. ComfyUI is a powerful and flexible graphical user interface for Stable Diffusion, allowing users to easily create, modify, and fine-tune AI-generated images with a node-based workflow.

## Features
- **Easy-to-Use UI**: Drag-and-drop node-based interface for intuitive control.
- **Customizable Prompts**: Generate images based on text descriptions.
- **Advanced Control**: Modify diffusion settings, image resolution, and sampling methods.
- **High-Quality Output**: Supports upscaling, inpainting, and model fine-tuning.
- **Multiple Model Support**: Load different Stable Diffusion models for diverse styles.

## Requirements
- **Operating System**: Windows, macOS, or Linux
- **Hardware**:
  - NVIDIA GPU with CUDA support (Recommended for faster generation)
  - Minimum 8GB VRAM for optimal performance
- **Software Dependencies**:
  - Python 3.10+
  - PyTorch (CUDA version recommended)
  - Stable Diffusion models
  - ComfyUI

## Installation
### Step 1: Clone the Repository
```sh
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI
```

### Step 2: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 3: Download Stable Diffusion Model
- Place the **Stable Diffusion checkpoint (.safetensors or .ckpt)** file in the `models` directory.

### Step 4: Run ComfyUI
```sh
python main.py
```

## Usage
1. **Start ComfyUI** and open the **web-based interface**.
2. **Load a Stable Diffusion model** from the settings panel.
3. **Enter a prompt** describing the image you want to generate.
4. **Adjust parameters** such as seed, steps, and guidance scale.
5. **Click Generate** and wait for the AI to process the image.
6. **Download or modify** the generated image using additional nodes.

## Example Prompt
```text
A futuristic cyberpunk city at night, neon lights reflecting on wet streets, flying cars in the background, ultra-detailed, cinematic lighting.
```

## Customization
- **Fine-tune the model** using LoRA or embeddings.
- **Experiment with different samplers** (Euler, DPM++, etc.).
- **Use control nodes** like depth maps or image-to-image transformations.

## Troubleshooting
- **CUDA Out of Memory**: Reduce image resolution or use `--lowvram` mode.
- **Slow Generation**: Lower the step count or switch to a lighter model.
- **Black Images**: Ensure model weights are correctly placed.

## References
- [Stable Diffusion GitHub](https://github.com/CompVis/stable-diffusion)
- [ComfyUI GitHub](https://github.com/comfyanonymous/ComfyUI)
- [Hugging Face Diffusion Models](https://huggingface.co/models)

## License
This project follows the **CreativeML Open RAIL-M License**, ensuring ethical use of AI-generated content.

---

Enjoy experimenting with AI-generated art! 🚀

