# dunyuliu.github.io

Personal academic site, served by GitHub Pages at https://dunyuliu.github.io.

- `template.html`: page layout and text (edit this)
- `pubs.json`: publication records (from ORCID + Crossref)
- `build.py`: renders `index.html` from the two above; run `python3 build.py` after editing, then commit both
- `cv/`: CV master copy (LaTeX; imported from Overleaf 2026-10-04). Edit `cv/cv/*.tex`, set the footer date in `cv/cv.tex`, then `cd cv && tectonic -X compile cv.tex` and commit `cv/cv.pdf` (linked from the site header)

Everything here is public: no phone number, home address, or ID/finance data. A new paper goes into both `pubs.json` and `cv/cv/publications.tex`.
