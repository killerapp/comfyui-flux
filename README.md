# ComfyUI and Flux.1 🖼️🚀

This guide will help you get up and running with Flux.1 in ComfyUI.

## Getting Started 🏁

1. Install ComfyUI following the instructions for your operating system.
2. Download the required model files and place them in the correct directories.
3. Load the included workflow file in ComfyUI.
4. Select the appropriate models in the workflow.

## Required Model Files 📁

### UNET Models (Place in ComfyUI/models/unet)
Download the compressed versions of Flux.1 from [Kijai/flux-fp8](https://huggingface.co/Kijai/flux-fp8/tree/main):
- flux1-dev-fp8.safetensors
- flux1-schnell-fp8.safetensors

### Text Encoders (Place in ComfyUI/models/clip)
Download from [comfyanonymous/flux_text_encoders](https://huggingface.co/comfyanonymous/flux_text_encoders/tree/main)

### VAE File (Place in ComfyUI/models/vae)
Download [ae.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-schnell/blob/main/ae.safetensors) from the Flux.1 HuggingFace repository

## Setting Up the Workflow 🛠️

1. Launch ComfyUI
2. Load the included workflow file
3. Select the appropriate models in the workflow nodes

Here's an example of how your ComfyUI workflow should look:

![ComfyUI Workflow Example](img/comfy-screen.png)

This image shows the correct way to wire the nodes in ComfyUI for the Flux.1 workflow. 🔌
