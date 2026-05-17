# Matched-Magnitude Controls for Causal Testing of Spectral Mechanisms in Attention

Evgeny Vyaltsev ([ORCID 0009-0004-3712-6798](https://orcid.org/0009-0004-3712-6798)) and Daniil Vyaltsev

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20261207.svg)](https://doi.org/10.5281/zenodo.20261207)

A short methodological note. Mechanistic claims about the spectral
structure of attention are increasingly common but rarely subjected to a
causal test with a control for the *magnitude* of the intervention. This
note shows why that omission matters, gives a worked example in which a
natural intervention construction produced a treatment perturbation
10-30x larger than its control (an asymmetry that would have read as a
strong positive), and describes a three-part framework -- matched-magnitude
intervention, random-spectrum baseline, pre-registered outcome criteria --
that converts the same hypothesis into a correct pre-registered null.

## Contents
- `matched_controls_note.tex` -- the note (LaTeX source)
- `matched_controls_note.pdf` -- compiled, 6 pages
- `figures/matched_magnitude.png` -- the matched-magnitude verification figure

## Build
`pdflatex matched_controls_note.tex` (twice). Standard packages only.

## Relation to other work
This note is the methodological companion to *The Spectral Gap-Statement*.
The ablation experiment whose construction it analyses, and the full data,
live with that research record, in the release that documents the closed
research program: https://doi.org/10.5281/zenodo.20261082. This note
stands alone: it is about causal-testing methodology, not about any
particular spectral claim.

## Citation
If you use this note, please cite it via its archived DOI:

> Vyaltsev, E. and Vyaltsev, D. (2026). *Matched-Magnitude Controls for
> Causal Testing of Spectral Mechanisms in Attention.* Zenodo.
> https://doi.org/10.5281/zenodo.20261207

```bibtex
@misc{vyaltsev2026matchedcontrols,
  author    = {Vyaltsev, Evgeny and Vyaltsev, Daniil},
  title     = {Matched-Magnitude Controls for Causal Testing of
               Spectral Mechanisms in Attention},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.20261207},
  url       = {https://doi.org/10.5281/zenodo.20261207}
}
```

## License
Text and figures: CC BY 4.0.
