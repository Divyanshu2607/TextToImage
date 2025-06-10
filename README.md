# Text-to-Image Generator using Stable Diffusion and Language Translation

This is a Google Colab-compatible Python project that translates input text into English (if needed) and generates an image using the [Stable Diffusion v2.1](https://huggingface.co/stabilityai/stable-diffusion-2-1) model from Hugging Face. It is optimized for both CPU and GPU and includes support for multiple languages via the `deep_translator` package.

---

## 🚀 Features

- 🔤 **Language Translation** using Google Translate API (`deep_translator`)
- 🎨 **Text-to-Image Generation** using Stable Diffusion 2.1
- ⚡ **GPU Acceleration** if available (uses `float16`)
- 💾 **Downloadable Image Output** via Google Colab
- 🧠 Configurable parameters for reproducibility and control

---

## 📦 Installation

Run the following commands in a **Google Colab** notebook cell:

```python
!pip install deep_translator -q
!pip install --upgrade diffusers transformers -q
