# Sources of Notes on Seminar Talks
This repository contains the LaTeX-sources of notes on some of 
my talks held in mathematical seminars at the University of Regensburg.
The notes will vary in detail, see the corresponding READMEs.

In case you have further questions (e.g. on the topics), do not hesitate to contact me.

## List of Talks
- [Spanier-Whitehead-Dualität](./spanier_whitehead_duality)
  (German), 24/05/2017
- [Steenrod Algebra](./steenrod_algebra),
  05/07/2017
- [Some Classical Results on Stable Homotopy Groups](./some_classical_results),
  18/10/2017
- [Localisation and Completion of Spectra](./localisation_completion_of_spectra),
  20/12/2017

## Cloning one Talk
To clone and work with the source of only one talk you can use 
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
