# WHU Beamer Theme

A Wuhan University Beamer presentation theme adapted from THU Beamer Theme, with a Chinese-language sample presentation and university logo.

Original Chinese documentation: [README.zh-CN.md](README.zh-CN.md).

## Requirements

A TeX distribution with XeLaTeX, BibTeX, Beamer, ctex, the packages imported by slide.tex, and suitable Chinese fonts. Make is optional but used by the supplied build.

## Getting started

```sh
make
# Produces slide.pdf
make clean
```

## Project structure

| Path | Purpose |
| --- | --- |
| `WHU.sty` | Theme style |
| `slide.tex` | Editable example presentation |
| `ref.bib` | Bibliography |
| `logo` | University logo |
| `img` | Example figures |
| `Makefile` | XeLaTeX/BibTeX build sequence |

## Configuration and limitations

Use XeLaTeX rather than pdfLaTeX for the Chinese sample. Edit author/title/institute/date and slide content in `slide.tex`. `make clean-all` also removes generated PDFs.

## Development and validation

Build the sample and inspect fonts, bibliography, figures, and navigation in the resulting PDF.

## Related projects and attribution

Adapted from [THU Beamer Theme](https://github.com/Trinkle23897/THU-Beamer-Theme).

## License

See [LICENSE](LICENSE).
