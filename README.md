# Sources of Notes on Seminar Talks
This repository contains the LaTeX-sources of notes on some of 
my talks held in mathematical seminars at the University of Regensburg.
The notes will vary in detail, see the corresponding READMEs.

In case you have further questions (e.g. on the topics), do not hesitate to contact me.

## List of Talks
Links to repositories with further talks:
- [Das zahme Symbol der Milnor-K-Theorie und diskrete Bewertungsringe](https://github.com/gesina/k-theory)
  (German), 01/07/2015
- [Isogenien elliptischer Kurven](https://github.com/gesina/isogenien)
  (German), 25/06/2016
- [Bachelor thesis: Neron-Modelle elliptischer Kurven](https://github.com/gesina/neron_models)
  (German), 28/09/2016
- [Lefschetz fixed-point formula for étale cohomology](https://github.com/gesina/lefschetz_fixed-point_formula),
  12/06/2017
  
Talks in this repository:
- [Spanier-Whitehead-Dualität](./spanier_whitehead_duality)
  (German), 24/05/2017
- [Steenrod Algebra](./steenrod_algebra),
  05/07/2017
- [Some Classical Results on Stable Homotopy Groups](./some_classical_results),
  18/10/2017
- [Localisation and Completion of Spectra](./localisation_completion_of_spectra),
  20/12/2017
  
Links to non-mathematics talks:
- [Overview on a selection of typographical topics](https://github.com/gesina/typography_talk),
  11/06/2016

## Cloning one Talk
To clone and work with the source of only one talk of this repository you can use 
git's [sparse-checkout](https://git-scm.com/docs/git-read-tree#_sparse_checkout) feature
(and, if no history is needed, [shallow cloning](https://git-scm.com/docs/git-clone)) 
as follows (git version >=1.9)

```bash
# create repository <repo> with corresponding remote
git init <repo>
cd <repo>
git remote add origin <url>
# enable sparse-checkout: 
# Only stuff/folders within .git/info/sparse-checkout are checked out.
git config core.sparsecheckout true
echo "<talk folder name>/" >> .git/info/sparse-checkout
# pull talk; 
# if no history is needed, do a shallow clone with --depth 1
git pull origin master
```
