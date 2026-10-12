# Chapter 4: Domain decomposition for physics-informed neural networks

**Authors:** Victorita Dolean, Alexander Heinlein, and Ben Moseley

This folder accompanies the chapter on overlapping and non-overlapping domain
decomposition approaches for PINNs.

## Setup and execution

**Installation:**
```bash
pip install -r requirements.txt
```

**Running the example:**
```bash
jupyter notebook example_fbpinn_d3m_poisson1d.ipynb
```
Run all cells in order. The notebook solves the 1D Poisson equation using FBPINNs and D3M, comparing both methods across different numbers of subdomains. Output plots are saved to `plots/`.

**Hardware:** CPU is sufficient; no GPU required.  
**Approximate runtime:** ~5–10 minutes on a modern laptop CPU.
