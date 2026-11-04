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

Manuscript source lives here. The public experiment code and reproduction
instructions for the main experiments are available separately at:
  https://github.com/yonatansverdlov/Canonization

Do not assume that the license of experiment scripts covers all
third-party datasets or derived weights.
