# LaTeX templates

Here are some useful LaTeX templates.

## Requirements

```shell
sudo apt-get install texlive-full biber
```

## How to compile

```shell
pdflatex -halt-on-error File
biber File
makeglossaries File
pdflatex -halt-on-error File
pdflatex -halt-on-error File
```