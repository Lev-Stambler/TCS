# Reducing 3SAT to Zero-Finding for Constant-Jacobian Polynomial Maps

This repository contains a self-contained proof of an explicit polynomial-time
reduction from 3SAT to deciding whether an integer-coefficient polynomial map
with constant nonzero Jacobian determinant has a real zero.

- [`main.tex`](main.tex) is the LaTeX source.
- [`main.pdf`](main.pdf) is the compiled paper.
- [`compact_tweet.tex`](compact_tweet.tex) is a 16:9 summary card.
- [`compact_tweet.png`](output/pdf/compact_tweet.png) is the 1600x900 image
  ready to attach to a post.

## Build

With a current TeX Live installation:

```sh
latexmk -pdf main.tex
```

The appendix contains an exact SymPy verification of the fixed polynomial
gadget's Jacobian and Gröbner-basis certificates.
