# Mys AI - LINKs
En esta seccion hallaras los diferentes modelos que utilizan los workflows. 
<img width="512" height="512" alt="ComfyUI_temp_ieidg_00005_" src="https://github.com/user-attachments/assets/7f79f9c3-f6de-4145-8351-c9d2697a37fc" />



# **WORKFLOW GOTY V2_**


MODELO DE DIFUSIÓN -23 GB:
https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors?download=true 

CLIP LOADERS
https://huggingface.co/zer0int/CLIP-GmP-ViT-L-14/resolve/main/ViT-L-14-TEXT-detail-improved-hiT-GmP-TE-only-HF.safetensors?download=true 

https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/t5xxl_fp16.safetensors?download=true 

VAE
https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/ae.safetensors?download=true 

CONTROLNET - 23 GB
https://huggingface.co/jasperai/Flux.1-dev-Controlnet-Depth/resolve/main/diffusion_pytorch_model.safetensors?download=true 

QUE NODOS UTILIZA EL WORKFLOW??

https://github.com/Fannovel16/comfyui_controlnet_aux 
https://github.com/pythongosssss/ComfyUI-Custom-Scripts 
https://github.com/rgthree/rgthree-comfy 
https://github.com/yolain/ComfyUI-Easy-Use 
https://github.com/kijai/ComfyUI-KJNodes 
https://github.com/kijai/ComfyUI-Florence2 
https://github.com/cubiq/ComfyUI_essentials 
https://github.com/chrisgoringe/cg-use-everywhere 
https://github.com/Pixelailabs/Save_Florence2_Bulk_Prompts 

LINKS LORA VTA: https://huggingface.co/Jotaplop/VITTO/tree/main

# **SINTAXIS PARA RUNPOD:**

Instalar Archivos "wget"
Instalar Archivos github "git clone"
Instalar Archivos que necesitan Token: 

**pip install huggingface_hub**

wget --header="Authorization: Bearer TOKEN HERE" \
"https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors?download=true"

wget --header="Authorization: Bearer TOKEN HERE" \
"https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/ae.safetensors?download=true"

