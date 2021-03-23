# Wix's Website Usability Analysis

![test](https://github.com/lparolari/wix-usability-analysis/workflows/test/badge.svg)

> A comprehensive report on usability issues for
> [wix.com](https://wix.com) website.

## Get the report

[🚀 Read the report](https://github.com/lparolari/wix-usability-analysis/releases/download/v1.0/report.zip)

## Build the report from sources

Clone the project

```bash
git clone https://github.com/lparolari/wix-usability-analysis
```

Compile the latex source (by default this will use a docker-based
latex compilation)

```bash
make
```

### Build strategy

If you want to use other latex releases we provide some build
strategies:

- build with **docker-based pdflatex by blang** (_recommended_)

```bash
make BUILD_STRATEGY=pdf3
```

- build with **docker-based tectonic latex by dxjoke**

```bash
make BUILD_STRATEGY=pdf2
```

- build with **pdflatex**

```bash
make BUILD_STRATEGY=pdf1
```

## ⚠️ Disclaimer ⚠️

> This report is not official. The report is intended to be **MY
> PERSONAL OPINION** on Wix website. I analysed it only for academic
> puposes in order to sustain the Web Information Management exam at
> University of Padua in 2021. If this is hurting someone please let
> me know and I will remove it.

## Author

Luca Parolari

- GitHub: [https://github.com/lparolari](https://github.com/lparolari)
- Email: <luca.parolari23@gmail.com>
- Telegram: [@lparolari](https://t.me/lparolari)

## License

This project is MIT licensed. See [LICENSE](LICENSE) file.
