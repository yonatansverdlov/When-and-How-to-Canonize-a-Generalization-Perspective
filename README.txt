NeurIPS 2026 camera-ready LaTeX source

Compile either of the following entry points:
  - arxiv.tex            : camera-ready paper with actual author metadata
  - wrapper_neurips.tex  : equivalent camera-ready wrapper

Both use the [final,main] NeurIPS 2026 style, shared sections in common/,
the bibliography in can.bib, and the mandatory checklist in
nips/checklist.tex.

Example:
  latexmk -pdf -interaction=nonstopmode arxiv.tex

Before submitting the resulting PDF, confirm the funding and competing-
interests disclosure with all coauthors, review third-party asset licenses,
and verify all linked code/data statements.

This repository contains the manuscript sources; it does not by itself
establish that the experimental code and datasets are publicly released.
