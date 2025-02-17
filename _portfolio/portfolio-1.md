---
title: "Stable Diffusion Image Generator"
excerpt: "<br/>Implemented Stable Diffusion for Image-to-Image and Text-to-Image setting.<img src='../images/portfolio/sdm.png' style='width:50%;'>"
collection: portfolio
---


In this project, I developed a [Stable Diffusion Image Generator](https://huggingface.co/spaces/ailm/Stable-diffusion-inkpen-test), hosted on Hugging Face Spaces. The application supports both Text-to-Image and Image-to-Image generation, allowing users to create high-quality images from text prompts or modify existing images using diffusion models.

To ensure responsible AI usage, I integrated a profanity filter, which loads custom words from a JSON file and prevents inappropriate content in prompts. The model is optimized for CUDA to leverage GPU acceleration, making the inference process efficient.

You can try the app [here](https://huggingface.co/spaces/ailm/Stable-diffusion-inkpen-test) and explore the code [here](https://huggingface.co/spaces/ailm/Stable-diffusion-inkpen-test/tree/main).