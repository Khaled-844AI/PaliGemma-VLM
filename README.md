# PaliGemma-VLM

Siglip-VLM (Vision-Language Model) is an end-to-end implementation of a multimodal transformer architecture that integrates both **vision** and **language understanding**.  
This repository contains a full reimplementation of the model’s core components from scratch, including all major building blocks required for training and inference.

## 🚀 Features

- **RMSNorm** — a lightweight normalization technique improving stability during training.  
- **Attention Mechanisms** — full self-attention and cross-attention layers with support for multi-head configurations.  
- **Encoder–Decoder Architecture** — modular transformer blocks for both visual and textual processing.  
- **Feedforward Layers (MLP)** — custom implementations using gated activation functions (e.g., GELU, SwiGLU).  
- **KV Cache** — optimized key–value caching for efficient autoregressive decoding.  
- **Vision Encoder** — processes image embeddings using convolutional or patch-based input layers.  
- **Text Decoder** — generates natural language conditioned on visual context.  
- **Tokenizers & Projection Layers** — connect vision and text modalities seamlessly.  

## 🧠 Purpose

The goal of this project is to **understand and replicate the internals of modern vision-language models** such as CLIP, Flamingo, or Gemini by implementing every module manually and studying their interactions.

## 🧩 Tech Stack

- **Python**
- **PyTorch**
- **NumPy**
- **Matplotlib (for visualization)**
- **Hugging Face tokenizers (optional)**

## 🧪 Future Work

- Integrate pretrained weights for benchmarking  
- Add fine-tuning scripts for custom datasets  
- Implement evaluation metrics (BLEU, CIDEr, CLIPScore)  
- Extend support for mixed precision (FP16)

---

Would you like me to make this sound more **research-style (paper-like)** or **developer-friendly (for GitHub README)**?



