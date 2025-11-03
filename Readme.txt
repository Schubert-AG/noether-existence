# Noether Principle of Existence: Code & Supplementary Materials

This repository contains the code and supplementary materials for the manuscript:  
**"Information and Spacetime: A Generalized Noether Theorem des Seins"**  
by Axel G. Schubert (2025).

## Overview
- **Core Idea**: Extends Noether's theorem to information geometry, deriving spacetime from invariance of existence.
- **Key Files**:
  - `main.tex`: Full LaTeX source (MDPI format).
  - `references.bib`: Bibliography.
  - `sympy_verify.py`: Symbolic verification using SymPy (reproduces Fisher metric and geodesics).

## Reproduction Instructions
1. Install dependencies: `pip install sympy numpy matplotlib` (aus dem Code-Interpreter-Tool).
2. Run SymPy verification: `python sympy_verify.py`  
   Output: Fisher metric components (V_xx, V_tt, etc.) confirming Minkowski signature.
3. Compile LaTeX: `pdflatex main.tex` → `bibtex main` → `pdflatex main.tex` ×2.

## License
CC BY 4.0 (same as manuscript).

Questions? Contact: schubert.ag@posteo.de