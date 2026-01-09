# nanoGPT-learning-project
Experiments with nanoGPT for text generation (Shakespeare-style text and song lyrics), inspired by Andrej Karpathy’s nanoGPT.


This repository contains my experiments with **nanoGPT**, a lightweight GPT-style language model introduced by **Andrej Karpathy**.

The goal of this project is to understand:
- How GPT-style models are trained
- How training iterations affect text quality
- How nanoGPT can be adapted to different datasets

---

## 📌 Projects Included

### 1. Shakespeare Text Generation
- Trained nanoGPT on a Shakespeare dataset
- Observed output quality at different training iterations (500, 1000)
- Generated Shakespeare-style text samples

📓 Notebook: `notebooks/nanoGPT_shakespeare.ipynb`  
🎥 Output video: `outputs/shakespeare_output.mp4`

---

### 2. Song Lyrics Generation
- Trained nanoGPT on a song lyrics dataset
- Analyzed stylistic patterns learned by the model
- Generated original song-like text

📓 Notebook: `notebooks/nanoGPT_song_generation.ipynb`  
🎥 Output video: `outputs/song_generation_output.mp4`

---

## ⚙️ Tech Stack
- Python
- PyTorch
- nanoGPT architecture
- Google Colab

---

## 🙏 Acknowledgements
This project is **inspired by Andrej Karpathy’s nanoGPT**:
https://github.com/karpathy/nanoGPT

This repository does **not** copy or redistribute the original nanoGPT code.
All notebooks contain my own experimental runs and outputs.

---

## 📈 Learning Outcome
This project helped me understand:
- Transformer architecture fundamentals
- Training loops and loss behavior
- The impact of training iterations on text generation
