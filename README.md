# biblatex-lncs
[![Build](https://github.com/mgttlinger/biblatex-lncs/actions/workflows/build.yml/badge.svg)](https://github.com/mgttlinger/biblatex-lncs/actions/workflows/build.yml)

BibLaTeX style for Springer Lecture Notes in Computer Science

## Introduction

This style extends the standard `BiBTeX` model by an `acronym` entry.

## Usage

```latex
\usepackage[backend=biber,
  style=lncs
]{biblatex}
```

## Status

I intend to maintain this fork and gladly accept pull requests and issues (although not committing myself to fixing any issue as required by the LPPL license). At the time of writing [@mgttlinger](https://github.com/mgttlinger) is the current maintainer in the sense of the LPPL license.

## Testing

For building the included `biblatex-lncs-test.tex` the `llncs` class from the Springer author guidelines needs to be in scope. The CI can get it via the ENV variable `LLNCS_CLS`.

## License

Copyright (c) 2022-2026 Merlin Humml and contributors

Forked from <https://github.com/neapel/biblatex-lncs.git>,
who forked from <https://github.com/jossco/biblatex-lncs.git>, by Joseph Scott
who forked from <https://github.com/gvdgdo/biblatex-lncs.git>, by Guido Governatori

This package may be distributed under the terms of the LaTeX Project
Public License, as described in lppl.txt in the base LaTeX distribution.
Either version 1.3c or, at your option, any later version.
