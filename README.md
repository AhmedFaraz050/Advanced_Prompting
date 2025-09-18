# 🧠 Week 3 Assignment - Advanced Prompting  
### Zero-Shot, Few-Shot, and Chain-of-Thought (CoT)

This repository contains my **Week 3 assignment** for experimenting with different prompting strategies and evaluating their effectiveness on reasoning tasks.  

---

## 📂 Contents
- `week3_assignment.ipynb` → Main Jupyter Notebook with tasks, outputs, evaluations.

---

## 📘 Overview
The assignment explores three prompting methods:

1. **Zero-Shot** → Direct question, no examples.  
2. **Few-Shot** → With 2+ examples for guidance.  
3. **Chain-of-Thought (CoT)** → Explicit step-by-step reasoning.  

Datasets used:
- `logic-puzzles.json`  
- `math-problems.json`  
- `reasoning-tasks.json`  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AhmedFaraz050/Advanced_Prompting.git
   cd Advanced_Prompting
   ```

2. Install dependencies:
   ```bash
   pip install notebook pandas
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `week3_assignment.ipynb` and run the cells.

---

## ✅ Results
| Task              | Zero-Shot | Few-Shot | CoT |
|-------------------|-----------|----------|-----|
| Logic Puzzle #1   | ❌ Incorrect | ✅ Correct | ✅ Correct (with reasoning) |
| Math Problem #1   | ❌ Wrong calc | ✅ Correct | ✅ Correct (step-by-step) |
| Reasoning Task #3 | ❌ Over-simplified | ✅ Correct | ✅ Correct (clear explanation) |
