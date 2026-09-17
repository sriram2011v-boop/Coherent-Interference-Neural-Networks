# Coherent Interference Neural Networks (CINN)
[![DOI](https://zenodo.org/badge/1374213364.svg)](https://doi.org/10.5281/zenodo.22810693)

**Paper 1 of a planned 12-paper research program.**

This repository contains the LaTeX source and compiled PDF for:

> **Coherent Interference Neural Networks: Phase-Based Multi-State Encoding for Parameter-Efficient Learning**
> Ventrapragada Sriram, Independent Researcher

## Abstract

We propose the Coherent Interference Neuron (CIN), a unit that represents
each connection with a complex amplitude-phase pair and combines inputs
through wave-like interference rather than linear summation, using a
low-rank amplitude/phase factorization and a Born-rule-inspired readout.
A CNN+CINN hybrid (301K params) reaches 75.1% test accuracy on CIFAR-10
after 50 epochs, vs. 55.4% for a parameter-matched MLP baseline (887K
params). We characterize a rank threshold effect and a depth-collapse
effect beyond two stacked CIN layers.

## Author

**Ventrapragada Sriram**
Independent Researcher, Visakhapatnam, India
Email: Sriram.2011.v@gmail.com
ORCID: _(add once registered)_

## Contents

- `cinn_paper.tex` — LaTeX source (arXiv-style)
- `arxiv.sty` — style file ([kourgeorge/arxiv-style](https://github.com/kourgeorge/arxiv-style))
- `cinn_paper.pdf` — compiled PDF
- `LICENSE` — CC-BY-4.0

## Building

```bash
pdflatex cinn_paper.tex
pdflatex cinn_paper.tex   # run twice for references
```

## Citing

A citable DOI via Zenodo will be added here once archived.

```bibtex
@misc{sriram2026cinn,
  author       = {Ventrapragada Sriram},
  title        = {Coherent Interference Neural Networks: Phase-Based Multi-State Encoding for Parameter-Efficient Learning},
  year         = {2026},
  howpublished = {GitHub},
  url          = {https://github.com/<your-username>/<repo-name>}
}
```

## Status

- [x] Draft written
- [ ] Reviewed / revised
- [ ] Pushed to GitHub
- [ ] Linked to ORCID
- [ ] Archived on Zenodo (DOI)

## Roadmap

This is the first of a planned 12-paper series extending the Coherent
Interference Neuron to transformers, GNNs, RNNs, reinforcement learning,
NLP, and generative models.
