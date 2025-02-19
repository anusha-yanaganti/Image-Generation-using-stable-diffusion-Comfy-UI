# Image Generation using Stable Diffusion & ComfyUI

## Overview
This project focuses on generating high-quality images using **Stable Diffusion** with **ComfyUI**, a modular and flexible GUI. ComfyUI provides a node-based workflow to efficiently manage image generation processes, allowing users to input prompts and generate images using deep learning models.

## Features
- **User-Friendly Interface:** ComfyUI's node-based design makes it easy to build workflows.
- **Text-to-Image Generation:** Generate images from textual descriptions using Stable Diffusion.
- **Customizable Workflows:** Users can modify nodes to tweak the output.
- **Image Inpainting & Editing:** Modify existing images with AI-powered tools.
- **Efficient Processing:** Optimized for GPU acceleration to generate images faster.

## Technologies Used
- **Stable Diffusion** (Image generation model)
- **ComfyUI** (Graphical interface for managing workflows)
- **Python** (Backend processing)
- **CUDA** (For GPU acceleration, if available)

## Installation
### Prerequisites
- **Operating System:** Windows/Linux/MacOS
- **Python:** 3.8 or later
- **Git** (to clone repositories)
- **GPU (Optional but recommended)**: NVIDIA GPU with CUDA support

### Setup Steps
1. Clone the ComfyUI repository:
   ```sh
   git clone https://github.com/comfyanonymous/ComfyUI.git
   cd ComfyUI
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download Stable Diffusion model files and place them in the `models/` folder:
   - You can download models from [Hugging Face](https://huggingface.co/CompVis/stable-diffusion-v1-4)
4. Run ComfyUI:
   ```sh
   python main.py
   ```

## Usage
1. **Launch ComfyUI**: Open the web-based UI after running `python main.py`.
2. **Enter Prompt**: Type a text prompt for image generation.
3. **Customize Nodes**: Adjust parameters like sampling steps and CFG scale.
4. **Generate Image**: Click the "Generate" button to produce an image.
5. **Save & Export**: Download the generated image for use.

## Example Workflow
1. **Input:** "A futuristic city at sunset, highly detailed, cinematic lighting."
2. **Processing:** Stable Diffusion model generates an image based on the input.
3. **Output:** AI-generated image of a futuristic cityscape.

## Future Enhancements
- Implement **higher-resolution image generation**.
- Add **support for LoRA and fine-tuned models**.
- Improve **inpainting and image editing capabilities**.
- Develop an **interactive API for automation**.


## License
This project is open-source under the **MIT License**.

---

For any issues or contributions, feel free to raise an issue or submit a pull request!
