# vietai_acv02_final_project
My submission for final project of Computer Vision and Applications - ACV02 by VietAI

# Required installation to run 
**1. ComfyUI and custom nodes** 
1.1 Base ComfyUI
https://github.com/comfyanonymous/ComfyUI

1.2 MagicClothing custom node for human model + base face generation + cloth merge
https://github.com/frankchieng/ComfyUI_MagicClothing

1.3 Fast face-swap nodes based on inswap_128
https://github.com/Gourieff/comfyui-reactor-node

1.4 Efficiency loader to load base SD checkpoint
https://github.com/jags111/efficiency-nodes-comfyui

1.5 IP-Adapter FaceID nodes
https://github.com/cubiq/ComfyUI_IPAdapter_plus

1.6 Various ComfyUI nodes including Face detailer module
https://github.com/ltdrdata/ComfyUI-Impact-Pack

**2. Model needed**
2.1 Face-swap model
https://huggingface.co/bongo2112/inswapper-128/tree/main

2.1 Cloth detection model
https://huggingface.co/ShineChen1024/MagicClothing/tree/main/early_access --  oms_diffusion_768_200000.safetensors

2.3 SD checkpoint for realistic human model generation and cloth generation
https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE/tree/main

2.4 SAM model
https://huggingface.co/spaces/abhishek/StableSAM/blob/main/sam_vit_h_4b8939.pth

2.5 BBox model
https://huggingface.co/datasets/Gourieff/ReActor/blob/main/models/detection/bbox/face_yolov8m.pt

2.6 IPAdapter Model
https://github.com/cubiq/ComfyUI_IPAdapter_plus
