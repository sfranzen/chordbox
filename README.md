# Chordbox

A LaTeX package for drawing string instrument chord diagrams

## Requirements

Chordbox depends on the following LaTeX packages:
* tikz;
* xifthen;
* xstrings.

## Installation

Please follow the procedure of your TeX distribution.

## Usage

After including `\usepackage{chordbox}` in your preamble, you can draw chord
boxes using the commands `\chordbox` and `\bchordbox` (for barre chords).
Examples:
```
\chordbox{Am}{x,0,2,2,1,0}
\bchordbox{Bm}{x,2,4,4,3,2}{2}
```

For more examples including the graphics, please refer to the documentation.

## Author

* [Steven Franzen](https://github.com/sfranzen)

## License

Copyright 2018 Steven Franzen

This work may be distributed and/or modified under the conditions of the LaTeX
Project Public License, either version 1.3 of this license or (at your option)
any later version. The latest version of this license is in
http://www.latex-project.org/lppl.txt and version 1.3 or later is part of all
distributions of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status "maintained".

The Current Maintainer of this work is Steven Franzen.
