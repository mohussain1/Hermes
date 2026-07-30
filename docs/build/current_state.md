# Hermes Current Build State

Date: 2026-07-30

## System

OS:
Ubuntu Linux

GPU:
NVIDIA RTX 3060 Laptop GPU 6GB VRAM

## ComfyUI

Location:

~/AI/ComfyUI

Status:

Working

## Installed Custom Nodes

- ComfyUI-Manager
- ComfyUI_IPAdapter_plus
- comfyui_controlnet_aux
- ComfyUI-Advanced-ControlNet
- ComfyUI-Impact-Pack
- was-node-suite-comfyui
- ComfyUI-Custom-Scripts
- hermes_library_save
- websocket_image_save

## Installed Models

### Diffusion

- sd3.5_medium.safetensors

Location:

models/diffusion_models/

### Text Encoders

- clip_g.safetensors
- clip_l.safetensors
- t5xxl_fp16.safetensors

Location:

models/text_encoders/

### VAE

- diffusion_pytorch_model.safetensors

Location:

models/vae/

### ControlNet

- sd3.5_large_controlnet_canny.safetensors
- sd3.5_large_controlnet_depth.safetensors

Location:

models/controlnet/

### CLIP Vision

- CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors

Location:

models/clip_vision/

## Current Goal

Build Hermes master-image generation pipeline:

Reference image
↓
IPAdapter identity preservation
↓
ControlNet composition control
↓
SD3.5 generation
↓
Face refinement
↓
Library save
