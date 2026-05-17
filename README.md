# 🧠 ML Study Notes — Month 1

> Documenting my machine learning journey from scratch — math, code, and intuition.

---

## 📒 Notebooks

### 1. Gradients & Partial Derivatives
> Theory and implementation built alongside StatQuest & 3Blue1Brown.

**Topics Covered**
- Partial derivatives — geometric intuition, not just the formula
- Gradient vector — direction of steepest ascent, computed by hand
- Jacobian matrix — derived from first principles
- MSE loss — full gradient derivation step by step
- Gradient descent — implemented from scratch with learning rate analysis

**What I Learned**
- Understood the gradient geometrically — it is the compass that tells a model which direction increases loss the fastest, so we move opposite to it
- Derived MSE gradients w.r.t. both weight and bias using the chain rule
- Discovered how learning rate controls the shrink factor — with α=0.1, every step multiplies x by 0.8
- Verified gradient descent converges to (0,0) in ~20 steps for f(x,y) = x² + y²
- Used SymPy to confirm hand-calculated derivatives symbolically

**Tools**
`Python` `NumPy` `Matplotlib` `SymPy` `Jupyter`

📓 Kaggle: [Gradients & Partial Derivatives](https://www.kaggle.com)
