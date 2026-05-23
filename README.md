All the resources for this assignment are present on the [Notion Site](https://wry-avocado-c9b.notion.site/Level-2-Artificial-Neural-Network-3622471f158d80f4a630ca7c1fd7a74f?pvs=74). Ensure that you go through it learn the concepts before proceesing with the assignments

#  Level 2: Artificial Neural Networks

Welcome to the Level 2 assignment. This task involves implementing and comparing two neural network models on the MNIST dataset — one built from scratch and one using PyTorch.

---

## Repository Structure
This is just a general idea, not a strict rule to follow

```
├── data/               # Place your dataset files here
├── src/
│   ├── scratch/        # Part 1: From-scratch implementation
│   │   ├── nn_scratch.ipynb
│   │   └── nn_scratch.py 
│   └── pytorch/        # Part 2: PyTorch implementation
│       ├── nn_pytorch.ipynb
│       └── nn_pytorch.py
├── report.pdf          # Final report (LaTeX → PDF)
└── requirements.txt    # Python dependencies
```

---

## Dataset

**MNIST** — [Download from Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv)

Place the CSV files inside the `data/` directory. Do not commit large dataset files to the repo.

---

## Tasks

### Part 1 — From Scratch (NumPy only)
- Implement forward propagation, backpropagation, and gradient descent using core Python and NumPy/Pandas.
- No deep learning frameworks (PyTorch, TensorFlow, etc.) allowed.

### Part 2 — PyTorch
- Re-implement the same architecture using PyTorch.

For each part, submit:
- One Jupyter Notebook (`.ipynb`)
- One equivalent standalone Python script (`.py`)

---

## Report

- Written in **LaTeX** via [Overleaf](https://www.overleaf.com/)
- Submitted as **PDF only**
- Must cover: convergence time, accuracy, memory usage, confusion matrix analysis, and a discussion of differences between the two implementations
- Focus on reasoning and analysis — not surface-level description

---

## Submission

1. Accept the assignment via the GitHub Classroom link on the CSOC website
2. Push all code and the report PDF to your forked repository before the deadline
3. Do **not** commit dataset files or model checkpoints

---

## Important Notes

- **LLM usage for code generation is refrained.** If used, it must be explicitly declared in the report — failure to do so results in disqualification.
- **Deadlines are absolute.** No extensions will be granted.
- For doubts, reach out to mentors on Discord.
