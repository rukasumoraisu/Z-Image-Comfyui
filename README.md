# Z-Image-ComfyUI

Do you want to generate images with better realism?  
Here is my ComfyUI workflow.

---

## ⚠️ Attention for Local ComfyUI Users

To use this workflow locally, you must install the required **custom nodes** and **models** listed below and place them in the correct directories.

---

## 🔴 Required Custom Nodes

- **ComfyUI-ReActor**  
- **ComfyUI-Impact-Pack**

These are mandatory. The workflow will not run correctly without them.

---

## 🟠 Required Models

### 1. Base Checkpoint (Realistic)
You must use **one realistic diffusion checkpoint** compatible with the workflow.

📌 Download from:  
- **CivitAI** – https://civitai.com

📂 Path:
ComfyUI/models/checkpoints/

### 2. VAE (Required)
A proper VAE is required to avoid color shifts and artifacts.

📂 Path:
ComfyUI/models/vae/

### 3. LoRA (Required)

The workflow uses a LoRA. You **must** install:

- **nicegirls LoRA**

📌 Download from:  
- **CivitAI** – https://civitai.com

📂 Path:
ComfyUI/models/loras/

⚠️ Without this LoRA, the **Load LoRA** node will fail.

### 4. Upscale Models
Recommended models:
- `4x-UltraSharp.pth`
- `RealESRGAN_x4plus.pth`
- `4x_foolhardy_Remacri.pth`

📌 Download from:  
- **OpenModelDB** – https://openmodeldb.info  
- **CivitAI** – https://civitai.com  

📂 Path:
ComfyUI/models/insightface/

## 📌 Summary

#### Custom Nodes
- ComfyUI-ReActor  
- ComfyUI-Impact-Pack  

#### Models
- 1 realistic **checkpoint**
- **VAE**
- **nicegirls LoRA**
- At least **1 upscale model**
- **ReActor face model (ONNX)**

## ☁️ Alternative (Cloud)

If you don’t want to install everything locally, I recommend **NordyAI**, which provides ComfyUI in the cloud with essential nodes and models already installed, offering a true plug-and-play experience.

///////////////////////////////////////////////////////////////////////
## ⚠️ Disclaimer

This workflow is provided **for educational and research purposes only**.

I am **not responsible** for how this workflow, its outputs, or any related models are used.  
Any results generated using this workflow are the **sole responsibility of the user**.

By using this workflow, you agree that you are responsible for complying with all applicable laws, platform rules, and ethical guidelines, including those related to image generation, likeness, and content usage.

**Use at your own risk.**

