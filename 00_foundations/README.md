# 00 – Foundations

Welcome to the starting point of `sam-learns-ML` — where I (re)build machine learning intuition from the ground up.

This section is about **graceful rigor**. I’m not just trying to get results; I want to understand why they work. 
These early experiments are simple on purpose. They’re here to build muscle memory, not show off.

## Goals

- **Internalize the fundamentals**: Understand loss functions, gradient descent, and the mechanics behind basic ML.
- **Learn by doing**: Every concept will be paired with hands-on code — no copy/pasting, no black boxes.
- **Build good habits**: Clean visualizations, readable code, meaningful experiment logs.
- **Fail forward**: Embrace debugging as part of learning. This is where I mess up, and give the mistake meaning by learning.

## Contents

### `bbs_first_model.ipynb`
**Goal:** Train a neural network on noisy data and visualize how it learns.

- Simulated data using `y = 3x + 2 + noise`
- Built a linear regression model in PyTorch (`nn.Linear`)
- Tracked loss over time using Mean Squared Error (MSE)
- Explored the effects of:
  - Learning rate
  - Weight and bias initialization
  - Training loop and gradient updates
- Visualized predictions vs truth
- Reflected on under/overfitting behavior
- Wrapped up with markdown Q&A and math explanation

💡 *Result:* A great baseline for understanding how even a simple model learns from data.

---

### `nonlinear_wiggles.ipynb`
**Goal:** Fit a nonlinear, “wiggly” function using deeper neural networks.

- Target function: `y = 3x + 2 + sin(5x) + noise`
- Added hidden layers with activations (`Tanh`, `ReLU`)
- Compared architectures: shallow, wide, and deep ("lasagna layers")
- Experimented with optimizers: `SGD` vs `Adam`
- Took model snapshots at key epochs for side-by-side plots
- Discussed slope misalignment, generalization, and learned curve shapes

🧠 *Highlight:* Switching to `Adam` with a `Tanh` lasagna layer gave the best performance on the noisy nonlinear signal.

---

I’m building this public lab notebook to prove that I know what I’m doing — even if it’s not obvious from my resume.
If you’re hiring, collaborating, or just curious: welcome aboard.

