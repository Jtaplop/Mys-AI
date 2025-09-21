# Mys AI - LINKs
En esta seccion hallaras los diferentes modelos que utilizan los workflows. 
<img width="512" height="512" alt="ComfyUI_temp_ieidg_00005_" src="https://github.com/user-attachments/assets/7f79f9c3-f6de-4145-8351-c9d2697a37fc" />

# **SINTAXIS PARA RUNPOD:**

Instalar Archivos "wget" // 
Instalar Archivos github "git clone"

_Instalar Archivos que necesitan Token:_
**pip install huggingface_hub**

wget --header="Authorization: Bearer TOKEN HERE" \
"https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors?download=true"

wget --header="Authorization: Bearer TOKEN HERE" \
"https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/ae.safetensors?download=true"

pip install insightface (Para el FaceSwap)

# **WORKFLOW GOTY V2_**


**MODELO DE DIFUSIÓN -23 GB:**  
- https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors?download=true 

**CLIP LOADERS**  
https://huggingface.co/zer0int/CLIP-GmP-ViT-L-14/resolve/main/ViT-L-14-TEXT-detail-improved-hiT-GmP-TE-only-HF.safetensors?download=true 

https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/t5xxl_fp16.safetensors?download=true 

**VAE**  
https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/ae.safetensors?download=true 

**CONTROLNET - 23 GB**  
https://huggingface.co/jasperai/Flux.1-dev-Controlnet-Depth/resolve/main/diffusion_pytorch_model.safetensors?download=true 

**QUE NODOS UTILIZA EL WORKFLOW??**

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

# **WORKFLOW FACESWAP KONTEXT**

**MODELO DE DIFUSION**  
https://huggingface.co/Comfy-Org/flux1-kontext-dev_ComfyUI/resolve/main/split_files/diffusion_models/flux1-dev-kontext_fp8_scaled.safetensors?download=true   

**DUAL CLIP LOADER**  
https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/clip_l.safetensors?download=true  
https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/t5xxl_fp8_e4m3fn.safetensors?download=true  

**LORA**  
https://civitai.com/api/download/models/2015589?type=Model&format=SafeTensor  

_QUE NODOS UTILIZA EL WORKFLOW??_

https://github.com/welltop-cn/ComfyUI-TeaCache  
https://github.com/cubiq/ComfyUI_FaceAnalysis  
https://github.com/liusida/ComfyUI-AutoCropFaces  
https://github.com/WASasquatch/was-node-suite-comfyui  
