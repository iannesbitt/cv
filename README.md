# Curriculum Vitae

Uses the [`moderncv`](https://www.ctan.org/pkg/moderncv) latex package.

## Build guide

Requirements (Ubuntu or Debian):
- `make`
- `latexmk`
- `texlive`
- `texlive-latex-extra`
- `texlive-xetex`
- `texlive-fonts-extra`

Command to install all:

```bash
sudo apt install make latexmk texlive texlive-latex-extra texlive-xetex texlive-fonts-extra
```

To build the PDF using the `Makefile`:

```bash
make
```

Extra commands:

`make show` - open built PDF
`make clean` - delete auxillary LaTeX files
`make all` - like `make` but re-builds all auxillary resources
