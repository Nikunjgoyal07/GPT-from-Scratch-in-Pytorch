# 🧠 mini-gpt-from-scratch

A minimal GPT-style language model — built 100% from scratch in PyTorch — trained to generate Shakespeare-like text.  
Includes full custom implementations of **Self-Attention**, **Multi-Head Attention**, **Masked Self-Attention**, and the complete GPT architecture.

---

## 📂 What’s Inside

| File | Description |
|------|--------------|
| `coding-self-attention-in-pytroch.ipynb` | Step-by-step notebook to implement **Self-Attention** from scratch |
| `coding-multi-head-attention-in-pytorch.ipynb` | Notebook for **Multi-Head Attention** implementation |
| `coding-masked-self-attention-in-pytroch.ipynb` | Notebook showing how **Masked Self-Attention** works for autoregressive text generation |
| `mini-gpt-from-scratch-in-pytorch.ipynb` | Complete **GPT model**: embeddings, positional encoding, attention blocks, feedforward layers, and text generation loop |
| `mini-gpt_from_scratch_in_pytorch.pth` | Trained GPT model weights |

---

## 🚀 Project Overview

This repo breaks down how a GPT works — piece by piece:
- **Self-Attention:** Learn how each token attends to others.
- **Multi-Head Attention:** Extend attention to multiple heads for richer representations.
- **Masked Attention:** Ensure the model predicts the next token without cheating.
- **Full GPT:** Assemble all blocks into a working generative language model.

I trained this GPT on a small Shakespeare dataset. Despite limited data, the model can generate short poetic lines that show the transformer’s power.

---

## ✨ Sample Output

Example generated text:



---

## ⚙️ Requirements

- Python 3.x
- PyTorch
- Jupyter Notebook

---

## 🏃‍♂️ Run It Yourself

1️⃣ Clone the repo:
```bash
git clone https://github.com/yourusername/mini-gpt-from-scratch.git
cd mini-gpt-from-scratch
pip install torch notebook
jupyter notebook
```

---

## 📚 How I Built It

- Started by understanding the original transformer paper.
- Broke it down into small parts: self-attention → multi-head → masking.
- Rebuilt the whole GPT block by block.
- Trained on Shakespeare’s text.
- Saved the final weights as `.pth`.

---

## 📫 Connect

If you find this helpful or want to learn more — feel free to reach out or fork the project.  
**Let’s build real AI, one block at a time.**

---

