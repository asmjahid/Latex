# LaTeX templates

Here are some useful LaTeX templates.

## Requirements

```shell
sudo apt-get install texlive-full biber
```
##OR
```shell
Miktex / Any other Latex Editor
```

## Download

```shell
http://miktex.org/download
```

## How to compile

```shell
pdflatex -halt-on-error File
biber File
makeglossaries File
pdflatex -halt-on-error File
pdflatex -halt-on-error File
```
