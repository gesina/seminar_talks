# Short summary on the Steenrod Algebra
These are the sources of a short summary (only main definitions,
statements, ideas for proofs) on my talk on the 
[Steenrod algebra](https://en.wikipedia.org/wiki/Steenrod_algebra).
The talk was held on 05/07/2017 during the seminar
*Stable Homotopy Theory* at the University of Regensburg.
The seminar was supervised by
[Dr. Georgios Raptis](https://www.researchgate.net/profile/George_Raptis).

## Structure
- main file (for compilation): `steenrod_algebra.tex`
- bibliography: `steenrod_algebra.bib`

## Compilation
(Tested) preliminaries: [`TeXLive 2017` Distribution](https://www.ctan.org/pkg/texlive)

For compilation execute the following commands

```bash
lualatex steenrod_algebra.tex
biber steenrod_algebra
lualatex steenrod_algebra.tex
```
