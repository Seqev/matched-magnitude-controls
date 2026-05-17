# Matched-Magnitude Controls for Causal Testing of Spectral Mechanisms in Attention

Evgeny Vyaltsev and Daniil Vyaltsev

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
This note is the methodological companion to *The Spectral Gap-Statement*
(https://doi.org/10.5281/zenodo.20257482). The ablation experiment whose
construction it analyses, and the full data, live with that research
record. This note stands alone: it is about causal-testing methodology,
not about any particular spectral claim.

## License
Text and figures: CC BY 4.0.
