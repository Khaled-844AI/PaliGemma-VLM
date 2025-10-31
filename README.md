# PaliGemma-VLM

**PaliGemma-VLM (Vision-Language Model)** is an end-to-end implementation of a multimodal transformer that integrates both **vision** and **language understanding**.  
This repository provides a complete reimplementation of the model’s internal architecture, built from scratch, including all the fundamental components required for both **training** and **inference**.

## 🚀 Features

- **RMSNorm** — lightweight normalization improving training stability.  
- **Attention Mechanisms** — includes full self-attention and cross-attention with multi-head support.  
- **Encoder–Decoder Architecture** — modular transformer blocks designed for visual and textual processing.  
- **Feedforward Layers (MLP)** — custom implementations with gated activations (e.g., GELU, SwiGLU).  
- **KV Cache** — optimized key–value caching for efficient autoregressive decoding.  
- **Vision Encoder** — extracts and processes image embeddings via convolutional or patch-based inputs.  
- **Text Decoder** — generates coherent text conditioned on visual embeddings.  
- **Tokenizers & Projection Layers** — seamlessly bridge the vision and text modalities.  

## 🧠 Purpose

The goal of this project is to **explore and reproduce the internal mechanisms of modern vision-language models**—such as CLIP, Flamingo, and Gemini—by manually implementing and analyzing every module to gain a deeper understanding of their design and functionality.

## 🧩 Tech Stack

- **Python**
- **PyTorch**
- **NumPy**
- **Hugging Face Tokenizers** (optional)

## 🧪 Future Work

- Integrate pretrained weights for benchmarking  
- Add fine-tuning pipelines for custom multimodal datasets  
- Implement evaluation metrics (BLEU, CIDEr, CLIPScore)  
- Extend support for **mixed-precision (FP16)** and **distributed training**
