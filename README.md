# Neural Generative Models in Practice

**GAMEX — Edinburgh Summer School on Generative AI for Extremes**  
**The University of Edinburgh · 8-11 September 2026** <br>
[GAMEX Summer School website](https://gamex-network.github.io/school/)

This repository contains materials for a 90-minute pratical session on **Neural generative models in practice** with PyTorch by [**Johnny Myung Won Lee**](https://webhomes.maths.ed.ac.uk/~s1687781).
 
The practical compares two tractable generative approaches on the same synthetic Edinburgh Airport arrival-trajectory problem:

1. a **Autoregressive Transformer**, and
2. a **Normalising Flow**.

The aim is to connect the probability models to the PyTorch code used to train, evaluate, sample from, and diagnose them.

---

## Practical materials

| File | Topic | Main representation |
| --- | --- | --- |
| [`01_gamex_transformer.ipynb`](01_gamex_transformer.ipynb) | Autoregressive transformer | Discrete spatial tokens |
| [`02_gamex_normalising_flows.ipynb`](02_gamex_normalising_flows.ipynb) | Real NVP Normalising flow | Continuous 60-dimensional trajectories |
| `handout.pdf` | Practical handout | Session overview, key equations and exercises |

---


## Requirements

Recommended software:

- Python 3.11+
- PyTorch 2.10+
- NumPy
- Matplotlib
- JupyterLab
- Git

A **CPU is sufficient** for the practical. The current notebooks select CUDA when it is available and otherwise use CPU.

---

## Installation

Clone the repository and create a virtual environment:

```bash
git clone https://github.com/gamex-network/gamex_summer_school.git
cd gamex_summer_school

python -m venv gamex
```

Activate it on macOS/Linux:

```bash
source gamex/bin/activate
```

or in Windows PowerShell:

```powershell
.\gamex\Scripts\Activate.ps1
```

Install the required packages:

```bash
python -m pip install --upgrade pip
python -m pip install torch numpy matplotlib jupyterlab
```

Then launch JupyterLab:

```bash
jupyter lab
```

Open the notebooks in order:

```text
01_gamex_transformer.ipynb
02_gamex_normalising_flows.ipynb
```

Run the first code cell to confirm the installed PyTorch version and loaded compute device.


## Session
**Neural Generative Models in Practice**  
Edinburgh Summer School on Generative AI for Extremes  
University of Edinburgh  
8 September 2026

Repository: https://github.com/gamex-network/gamex_summer_school
