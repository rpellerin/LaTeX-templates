# LaTeX templates

Here are some useful LaTeX templates.

## Requirements

```shell
sudo apt-get install texlive-full
```

## How to compile

```shell
pdflatex -halt-on-error File && pdflatex -halt-on-error File && bibtex File && makeglossaries File && pdflatex -halt-on-error File && makeglossaries File && pdflatex -halt-on-error File && pdflatex -halt-on-error File
```