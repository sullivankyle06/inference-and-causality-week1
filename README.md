# Sessions 1 and 2 — Inference and Causality

This repository contains the materials for **Sessions 1 and 2** of *Inference and Causality*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---


### Session Overview

This first session introduces the concept of **statistical inference** — how we draw conclusions about unknowns from data — and contrasts the two main paradigms in statistics: **Frequentist** and **Bayesian** inference.  
Students set up their GitHub environment, fork the session repository, and work through two Jupyter notebooks.

---

### Learning Objectives

By the end of this session, you should be able to:

- Understand the difference between **Frequentist** and **Bayesian** interpretations of probability.  
- Apply **Bayes’ theorem** to simple examples.  
- Update beliefs based on new evidence.  
- Use **GitHub** to collaborate and submit notebook work.

---

### Key Concepts

| Concept | Description |
|----------|--------------|
| **Frequentist Inference** | Parameters are fixed but unknown; data is random. |
| **Bayesian Inference** | Parameters are uncertain; beliefs are updated with data. |
| **Bayes’ Theorem** | |
| **Likelihood / Prior / Posterior** | Components of Bayesian reasoning: how data updates what we believe. |

---

### Example Problems

- **Cookie Problem**  
  Use Bayes’ theorem to find which bowl a vanilla cookie likely came from.  

- **Dice Problem**   
  Compute posterior probabilities when choosing between dice with different sides.  

- **Monty Hall Problem** 
  Simulate and reason why **switching doors doubles your chance** of winning the car.

---

### Hands-On Notebooks

| Notebook | Topic | Description |
|-----------|--------|-------------|
| `1_InferenceAndCausality_Week1_Probability.ipynb` | Probability | Core concepts and simple probability updates |
| `2_InferenceAndCausality_Week1_BayesTheorem.ipynb.ipynb` | Monty Hall Simulation | Applying Bayesian reasoning with Python |

---

### Exercise

Finish both notebooks and **commit** your solutions to your forked repository.  
Optional: Propose a new scenario where either Frequentist or Bayesian inference is more suitable.



### License & Attribution
The notebooks of this week are adapted in part from Think Bayes 2 by Allen B. Downey,
available at https://allendowney.github.io/ThinkBayes2/
,
and used under a CC BY-NC-SA 4.0 License
.
© Allen B. Downey — Modifications © 2025 Narges Chinichian.

---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```
