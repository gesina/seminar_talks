# Localisation and Completion of Spectra
These are the sources of some notes on my talk
on localisation and completion of spectra.
The talk was held on 20/12/2017 during the seminar
*Stable Homotopy Theory II* at the University of Regensburg.
The seminar was supervised by
[Dr. Georgios Raptis](https://www.researchgate.net/profile/George_Raptis)
and [Dr. Markus Land](http://markus-land.de/).

The talk contained the main definitions and major properties both of
(P-)localisation and (P-)completion. Proofs are sketched within the
notes.

## Structure
- main file (for compilation): `localisation_completion.tex`
- bibliography: `localisation_completion.bib`

## Compilation
(Tested) preliminaries: [`TeXLive 2017` Distribution](https://www.ctan.org/pkg/texlive)

For compilation execute the following commands

```bash
lualatex localisation_completion.tex
biber localisation_completion
lualatex localisation_completion.tex
```
