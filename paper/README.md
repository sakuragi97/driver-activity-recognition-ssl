# ITSC 2024 paper: LaTeX source

**3D Skeleton-Based Driver Activity Recognition Using Self-Supervised Learning**<br>
David J. Lerch, Yasser El Bachiri, Manuel Martin, Frederik Diederichs, Rainer Stiefelhagen. IEEE ITSC 2024.
DOI: [10.1109/ITSC58415.2024.10920160](https://doi.org/10.1109/ITSC58415.2024.10920160)

📄 Compiled author version: [`Lerch_ElBachiri_ITSC2024_SkelDINO-SAM_author-version.pdf`](Lerch_ElBachiri_ITSC2024_SkelDINO-SAM_author-version.pdf)

## Build

The paper uses the IEEE `ieeeconf` class and `biblatex` with the BibTeX backend (`style=ieee`).

```bash
cd source
latexmk -pdf paper.tex        # pdfLaTeX (uses Times)
# or
tectonic -X compile paper.tex # XeTeX (switches to TeX Gyre Termes, a Times clone)
```

On Overleaf, upload the contents of `source/` and set `paper.tex` as the main document.

## Layout

| File | Content |
|---|---|
| `paper.tex` | Preamble, authors, acknowledgment |
| `content/00_abstract.tex` … `06_conclusion.tex` | One file per section |
| `figures/` | Fig. 1 (`darssl.png`) and Fig. 2 (`principle.png`) |
| `references.bib` | The 36 references cited in the paper |
| `ieeeconf.cls`, `IEEEtran.bst` | IEEE conference template files |

<sub>© 2024 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses. The definitive version is available via the DOI above.</sub>
