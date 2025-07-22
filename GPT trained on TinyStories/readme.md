# 🧠 MiniGPT — A Tiny GPT from Scratch with BPE

This project is my from-scratch implementation of a **tiny GPT-style language model**, fully written in PyTorch — **no Hugging Face**, no pre-trained weights.

It includes:
- A custom **Byte Pair Encoding (BPE)** tokenizer (trained on my own dataset)
- A full **transformer block** with masked self-attention, feed-forward, and positional embeddings
- A next-token **language modeling loop**
- A simple text **generation script**
- Trained on short **story-style datasets** (like simple fairy tales)

---

## 🚀 Why I built this

Most people just copy Hugging Face and call `.generate()`.  
I wanted to really understand how GPTs **work under the hood**:
- How tokenization actually merges subwords
- How causal masking keeps the model autoregressive
- How the training loop fits together
- How to actually generate text token by token

---

## Example output:  once upon a time there was a small boy called Joe. Joe was three years old. One day Joe wanted to go to the park. He started to walk, and he saw something very special. On it was a special gift inside the tree. It had a picture of a rainbow. Joe thought that was a real piece of a small piece! Joe was so happy with his discovery. He thanked the man and waved goodbye to the flower. Joe hugged his mother tight, happy that he could help his mom and decided to tell him the story. Once upon a time, there was a wise man. He was very brave, old bird. The old man was walking through the forest when he saw a big, deep forest. He went up and saw