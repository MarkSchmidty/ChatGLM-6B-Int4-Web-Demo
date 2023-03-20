# ChatGLM-6B-Int4-Web-Demo
[![Launch In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MarkSchmidty/ChatGLM-6B-Int4-Web-Demo/blob/main/ChatGLM-6B_int4_Web_Demo.ipynb) <-- press here to launch the web demo

## About ChatGLM

ChatGLM-6B is an open bilingual language model based on [General Language Model (GLM)](https://github.com/THUDM/GLM) framework, with 6.2 billion parameters. With the quantization technique, users can deploy locally on consumer-grade graphics cards (only 6GB of GPU memory is required at the INT4 quantization level).

ChatGLM-6B uses technology similar to ChatGPT, optimized for Chinese QA and dialogue. The model is trained for about 1T tokens of Chinese and English corpus, supplemented by supervised fine-tuning, feedback bootstrap, and reinforcement learning wit human feedback. With only about 6.2 billion parameters, the model is able to generate answers that are in line with human preference.

## Links
- [16bit model on HuggingFace Hub](https://huggingface.co/THUDM/chatglm-6b/tree/main) (Requires 16GB RAM or VRAM)
- [4bit model on HuggingFace Hub](https://huggingface.co/THUDM/chatglm-6b-int4/tree/main) (Requires 6GB RAM or VRAM)
- [Full GitHub Repo with local GPU & CPU Deployment instructions](https://github.com/THUDM/ChatGLM-6B/blob/main/README_en.md#update)
