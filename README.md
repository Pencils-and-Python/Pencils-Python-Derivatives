
# ✏️ Pencils & Python: Derivatives in the Real World

Welcome to **Pencils & Python**, a project where we explore the power of calculus in real-world applications — from civil engineering to revenue optimization — all coded in Python.

This repository is organized to walk through foundational derivative rules (product, quotient, chain) using real-world case studies and visual modeling.

---

## 📚 What's Inside

### 🗂️ [docs/](./docs)
- Planning notebooks and structure files.
- Includes `structure.md`, post outlines, and scope planning.

### 🖼️ [figures/](./figures)
- Graphs, tables, and hand-drawn equations for visual storytelling.

### 📓 [notebooks/](./notebooks)
- Learning notebooks for:
  - Chain Rule
  - Product Rule
  - Quotient Rule
- Each subfolder includes symbolic, numeric, and visual analysis examples.

### 📝 [posts/](./posts)
- Final post drafts ready to publish.
- Includes full narrative notebooks like:
  - `SW_product_post.ipynb`: Stormwater pollutograph modeling with the product rule.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/pencil_and_python_derivatives.git
   cd pencil_and_python_derivatives
   ```

2. Install dependencies:
   ```bash
   conda create -n pencils python=3.10
   conda activate pencils
   conda env create -f environment.yml  # (or use a pip requirements.txt file)
   ```

3. Launch Jupyter Lab:
   ```bash
   jupyter lab
   ```

---

## 📌 Featured Example: Stormwater Pollutant Load

Using the **product rule**, we model how pollutant load changes during a storm using symbolic differentiation and time-series visualizations.

Includes:
- SymPy symbolic math
- Matplotlib graphs
- Realistic runoff modeling
- First-flush and exponential decay analysis

> Full write-up in [`posts/SW_product_post.ipynb`](./posts/SW_product_post.ipynb)

---

## 🧠 Why This Project?

Because calculus is more than textbook exercises — it’s a modeling tool. Whether you’re managing stormwater infrastructure, optimizing revenue, or understanding risk, these derivative rules help quantify change in meaningful ways.

Stay curious. Test your assumptions. And keep your pencils (and Python) sharp.

---

## 📎 License

MIT License. Feel free to fork, remix, and use for learning or teaching.

