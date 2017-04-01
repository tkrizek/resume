# Resume

## Dependencies

Tested with Linux Mint 18.1.

```console
$ apt install texlive xzdec
```

If you're using older texlive, set appropriate repositories for tlmgr.

```console
$ tlmgr option repository ftp://tug.org/historic/systems/texlive/2015/tlnet-final
```

Install LaTeX dependencies.

```console
$ tlmgr install europecv ucs babel babel-czech enumitem
```

## Compile

```console
$ pdflatex resume_cs.tex
```
