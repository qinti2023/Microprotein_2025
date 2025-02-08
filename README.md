# A Hidden Rule in Genetic Codes Shapes the Folding Landscape of Microproteins Derived from Non-canonical Translation
This repository contains Python code, Jupyter Notebooks, and data to reproduce the results presented in the manuscript “A Hidden Rule in Genetic Codes Shapes the Folding Landscape of Microproteins Derived from Non-canonical Translation.” The code is organized into two main sections:
## 1. Long-Range Interactions Calculation
### Layout
`long_interactions/pdb_to_cm.py : ` Simple Python script for computing protein contact maps from PDB files as described in Godzik and Skolnick, (1994). An edge is added between all non-adjacent pairs of amino acids where the euclidean distance between their alpha carbons are less then some threshold. <br>
`long_interactions/batch_calculate : `
## 2. Microprotein Stability Model

