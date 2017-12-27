# Some Classical Results on Stable Homotopy Groups
These are the sources of a short summary (only main definitions,
statements, ideas for proofs) on my talk
*Overview over some Classical Results*.
The talk was held on 18/10/2017 during the seminar
*Stable Homotopy Theory II* at the University of Regensburg.
The seminar was supervised by
[Dr. Georgios Raptis](https://www.researchgate.net/profile/George_Raptis)
and [Dr. Markus Land](http://markus-land.de/).

The talk concentrated on the stable homotopy groups of spheres, namely
its
[ring structure](https://en.wikipedia.org/wiki/Homotopy_groups_of_spheres#Ring_structure)
and identifying the 
[Hopf maps](https://en.wikipedia.org/wiki/Hopf_fibration) 
as non-trivial elements.

## Structure
- main file (for compilation): `some_classical_results.tex`
- bibliography: `some_classical_results.bib`

## Compilation
(Tested) preliminaries: [`TeXLive 2017` Distribution](https://www.ctan.org/pkg/texlive)

For compilation execute the following commands

```bash
lualatex some_classical_results.tex
biber some_classical_results
lualatex some_classical_results.tex
```
