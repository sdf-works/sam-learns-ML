# 📉 Loss Curves: Baby’s First Model Learns to Learn

This notebook walks through the absolute basics of machine learning model training using PyTorch.

We:
- Generate a clean linear dataset: `y = 3x + 2`
- Add a sprinkle of noise (chaos, realism, etc.)
- Build a single-layer linear model (`nn.Linear(1, 1)`)
- Train it using mean squared error loss and stochastic gradient descent
- Track the model's weight, bias, and loss over time
- Plot how well it learns the original function

Along the way we:
- Visualize how predictions change over epochs
- Look at why the model over/under-predicts early on
- Break down what's happening in the math behind each step

### ✨ Why this matters:
Loss curves help us understand *how* a model learns — how fast, how well, and when it might be struggling. This is the simplest possible version of that, built to be readable and intuitive from the ground up.

---

### 🗂 Files

- `bbs_first_model.ipynb` — full walkthrough notebook
- `README.md` — you're here

---

> This is part of the [`sam-learns-ML`](../..) project, a gentle, transparent, goblin-friendly guide to building up machine learning intuition from scratch.
