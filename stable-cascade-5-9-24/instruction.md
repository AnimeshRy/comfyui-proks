https://huggingface.co/stabilityai/stable-cascade/tree/main

stage_b.safetensors and stage_c.safetensors (you can use the bf16 versions) go in ComfyUI/models/unet

stage_a.safetensors goes in ComfyUI/models/vae

and this: https://huggingface.co/stabilityai/stable-cascade/blob/main/text_encoder/model.safetensors goes in the ComfyUI/models/clip/ folder to be loaded with the Load CLIP node in the workflow
