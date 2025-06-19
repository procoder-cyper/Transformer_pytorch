# 🔥 Transformer from Scratch: "Attention is All You Need" (NIPS 2017)

This repository contains a complete 💡 from-scratch implementation of the **Transformer** architecture as described in the groundbreaking paper:

> 📜 **"Attention is All You Need"**  
> ✍️ Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin  
> 🧠 NeurIPS 2017  
> [📄 View Original Paper (PDF)](./paper/NIPS-2017-attention-is-all-you-need-Paper.pdf)

---

## 🔍 Overview

The Transformer model revolutionized deep learning in sequence modeling by **removing recurrence altogether** and using only attention mechanisms — enabling ⚡faster training, 💯 better performance, and 🧱 cleaner architecture.

This implementation includes:
- 🏗️ Encoder-Decoder structure
- 🧮 Scaled Dot-Product Attention
- 🎯 Multi-Head Attention
- 🧭 Sinusoidal Positional Encoding
- ⚙️ Position-wise Feedforward Networks
- 🧱 Residual Connections + Layer Normalization
- 🔒 Masked decoding to preserve autoregression

---

## 🧠 Core Concepts

| Concept 🔑                      | Description 📘                                                                 |
|-------------------------------|--------------------------------------------------------------------------------|
| 💥 Scaled Dot-Product Attention | Calculates attention weights using dot products (scaled by √dimension)        |
| 🧠 Multi-Head Attention         | Enables parallel attention over multiple subspaces                            |
| 🧭 Positional Encoding          | Injects order-awareness using sin/cos positional signals                      |
| 🧱 Encoder-Decoder              | Maps input → latent → output via attention and feedforward layers            |
| 🕶️ Masked Attention             | Prevents the decoder from seeing future tokens during training               |

---




