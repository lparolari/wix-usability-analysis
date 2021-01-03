# Wix.com Usability Analysis

> A comprehensive report on usability issues for
> [wix.com](https://wix.com) website.

## Get the report

TODO: add release

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

## Author

Luca Parolari

- GitHub: [https://github.com/lparolari](https://github.com/lparolari)
- Email: <luca.parolari23@gmail.com>
- Telegram: @lparolari

## License

This project is MIT licensed. See [LICENSE](LICENSE) file.
