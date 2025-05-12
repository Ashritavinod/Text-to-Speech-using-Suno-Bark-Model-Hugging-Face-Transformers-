# 🗣Text-to-Speech using Suno Bark Model (Hugging Face Transformers)

This project demonstrates how to perform **text-to-speech (TTS)** conversion using the [Hugging Face `transformers`](https://huggingface.co/docs/transformers/index) library and the **`suno/bark-small`** pre-trained model. The audio is generated from a given input text and played directly within a Jupyter notebook environment.

---

##  Project Overview

This notebook performs the following tasks:

- Installs the necessary libraries (`transformers`, `torch`)
- Loads the pre-trained `suno/bark-small` model using the `pipeline` API
- Converts a text input to speech
- Plays the generated audio within the notebook

---

##  Quick Start

###  Installation

Install the required packages using:

```bash
pip install transformers torch
