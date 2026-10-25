# Master thesis

**Enhancing Vehicle Interior Action Recognition using Contrastive Self-Supervised Learning with 3D Human Skeleton Representations**<br>
Yasser El Bachiri. M.Sc. Artificial Intelligence and Data Science, Deggendorf Institute of Technology & University of South Bohemia. Submitted 20 September 2023.<br>
Carried out at Fraunhofer IOSB, Karlsruhe.

- 📄 [Full thesis (PDF)](El_Bachiri_2023_Master_Thesis.pdf)
- 📝 [Abstract (PDF)](El_Bachiri_2023_Master_Thesis_Abstract.pdf)
- 🎤 [Defense slides (PDF)](../slides/El_Bachiri_2023_Thesis_Defense_Slides.pdf)

## Build

The thesis uses KOMA-Script (`scrbook`) and BibTeX (`IEEEtran` style). The entry point is `thesis.tex`.

```bash
cd source
latexmk -pdf thesis.tex           # or: make
# or
tectonic -X compile thesis.tex
```

## Chapters

| File | Chapter |
|---|---|
| `chapter0.tex` | Introduction |
| `chapter1.tex` | Literature Review |
| `chapter2.tex` | Methodology |
| `chapter3.tex` | Experiments |
| `chapter4.tex` | Results |
| `chapter5.tex` | Conclusion |
