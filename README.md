# [AAAI 2025] ViPCap: Retrieval Text-Based Visual Prompts for Lightweight Image Captioning
[![arXiv](https://img.shields.io/badge/arXiv-2412.19289-red?logo=arXiv)](https://arxiv.org/abs/2412.19289)

## Code will be updated soon!

## 🎉 News 🎉
* [2024/12]: ViPCap is accepted at AAAI 2025 🔥
* [2024/10]: ViPCap achieves competitive benchmark in Lightweight image captioning & Plug-and-play ⚡

## ViPCap 🚀
![GitHub Actions](https://img.shields.io/badge/CI-GitHub%20Actions-green)
<img src="https://github.com/user-attachments/assets/4838ca40-5216-4bd9-874c-fa620032d923" width="100%" height="100%"> 

> Recent lightweight image captioning models using retrieved data mainly focus on text prompts. However, previous works only utilize the retrieved text as text prompts, and the visual information relies only on the CLIP visual embedding. Because of this issue, there is a limitation that the image descriptions inherent in the prompt are not sufficiently reflected in the visual embedding space. To tackle this issue, we propose ViPCap, a novel retrieval text-based visual prompt for lightweight image captioning. ViPCap leverages the retrieved text with image information as visual prompts to enhance the ability of the model to capture relevant visual information. By mapping text prompts into the CLIP space and generating multiple randomized Gaussian distributions, our method leverages sampling to explore randomly augmented distributions and effectively retrieves the semantic features that contain image information. These retrieved features are integrated into the image and designated as the visual prompt, leading to performance improvements on the datasets such as COCO, Flickr30k, and NoCaps. Experimental results demonstrate that ViPCap significantly outperforms prior lightweight captioning models in efficiency and effectiveness, demonstrating the potential for a plug-and-play solution.
