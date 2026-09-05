# TA Competency (TAC)

A bilingual (Chinese / English) documentation site for the **peer-led teaching-assistant (TA) training program** of the Department of Computer Science and Technology at Tsinghua University.

The site documents the design and content of the department's TA training: an **agile, iterative** program that has run since 2022, built around the different stages of a TA's growth. It is published at <https://thucstac.github.io/TAC/> and is generated with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Highlights

- **Fully bilingual** — every page is available in **中文** and **English** (built with `mkdocs-static-i18n`, language switcher in the top-right; English lives under `/en/`).
- **One page per session** — each semester has an index plus a page for every training session (independently organized for 2023 Autumn and 2024 Spring, and a per-semester index + session structure from 2024 Autumn onwards).
- **Curated references** — a [bibliography](docs/reference/readings.md) of computing-education papers/materials referenced in training, plus links to departmental TA-training programs and excellent courses/assignments.
- **Open feedback** — training feedback, attendance, and TA-reflection themes mined from the program's survey sheets.

## Related publication

The program is described in an experience report published at SIGCSE 2025:

> Liu, Runda; Chen, Shengqi; Chen, Jiajie; Niu, Songjie; Ma, Yuchun; Tang, Xiaofeng. *Iterative Design of a Teaching Assistant Training Program in Computer Science Using the Agile Method*. In Proceedings of the 56th ACM Technical Symposium on Computer Science Education V. 1 (SIGCSE 2025), 680–686. DOI: [10.1145/3641554.3701829](https://doi.org/10.1145/3641554.3701829)

## Building locally

Requires Python 3 and [mkdocs](https://www.mkdocs.org/).

```bash
python3 -m venv venv
source venv/bin/activate
pip install mkdocs-material mkdocs-static-i18n

# Preview at http://localhost:8000
mkdocs serve

# Build a static site into ./site
mkdocs build
```

The build produces:

- `site/` — the **中文** (default) version
- `site/en/` — the **English** version

## Deployment

Pushing to `main` (or `gh-pages`) triggers the [GitHub Actions workflow](.github/workflows/deploy-mkdocs.yml), which installs `mkdocs-material` and `mkdocs-static-i18n` and runs `mkdocs gh-deploy --force`.

## Contributing / feedback

Most of the material is in Chinese; the English version is maintained alongside. If you notice a typo, a broken link, or have a suggestion, please:

- Submit an [issue](https://github.com/THUCSTAC/TAC/issues), or
- Email <lrd25@mails.tsinghua.edu.cn>.

Contributions to new content, English translations, or additional references are welcome.

## License

Content is © the TAC team. See repository owners for terms.
