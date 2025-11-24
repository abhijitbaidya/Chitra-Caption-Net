# Chitra-Caption-Net

Chitra-Caption-Net is an automatic image captioning model that integrates both **computer vision** and **natural language processing** to generate descriptive captions from images. Image captioning requires identifying key objects, attributes, and relationships within an image and expressing them through natural language.

A crucial component of this task is **attention**—deciding *what* to describe and *how* to focus on specific regions of the image.  
To address this, Chitra Caption-Net introduces a **hybrid architecture** capable of handling both **spatial** and **sequential** information. The model incorporates **dense visual embedding** and an **implicit decoding Transformer** built with a custom encoder–decoder design.

---

## 🚀 Model Features

- Hybrid design for spatial + sequential data  
- Dense image embedding  
- Custom Transformer encoder and decoder  
- Implicit decoding for improved caption fluency  
- Optimized for multilingual datasets (Bangla and Nepali)  
- Outperforms existing models on benchmark datasets

---

## 📊 Dataset Evaluation

Chitra Caption-Net was evaluated on:

- **BAN-Cap**  
- **BanglaLekha**  
- **Flickr8k (Nepali Version)**  

The model achieved state-of-the-art performance:

| Dataset | BLEU-4 | METEOR | CIDEr |
|--------|--------|--------|-------|
| **BAN-Cap** | 20.86 | 26.61 | 21.85 |
| **BanglaLekha** | 62.86 | 67.16 | 60.57 |
| **Flickr8k (Nepali)** | 69.24 | 51.50 | 46.72 |

---

