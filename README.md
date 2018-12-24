lstfiracode
===========

The `lstfiracode` package defines `FiraCodeStyle`, to be used as
`\lstset{style=FiraCodeStyle}` with the [`listings`](https://ctan.org/pkg/listings)
package. This style contains almost all ligatures in Nikita Prokopov’s
[Fira Code](https://github.com/tonsky/FiraCode) family of fonts.
A new key `moreliterate` to `\lstset` is added, allowing additional user ligatures.
Additional support for source code listings using Fira Code
in the `verbatim` environment is available.

This package does NOT provide the Fira Code font files.
The newest version of the font files can be downloaded at the
[GitHub Fira Code Releases page](https://github.com/tonsky/FiraCode/releases).
Here is a sample preamble of a document:

    \documentclass{article}
    \usepackage{fontspec}
    \setmonofont{FiraCode-Regular.otf}[Contextuals=Alternate]
    \usepackage{listings}
    \usepackage[verbatim]{lstfiracode}
    \lstset{style=FiraCodeStyle,basicstyle=\ttfamily}

Contributing
------------

This package is maintained at https://github.com/RuixiZhang42/lstfiracode

Issues and pull requests are welcome.

Copyright and Licence
---------------------

    Copyright (C) 2018 by Ruixi Zhang <ruixizhang42@gmail.com>
    
    This work may be distributed and/or modified under the
    conditions of the LaTeX Project Public License, either version 1.3c
    of this license or (at your option) any later version.
    The latest version of this license is in
       https://www.latex-project.org/lppl.txt
    and version 1.3c or later is part of all distributions of LaTeX
    version 2005/12/01 or later.
    
    This work has the LPPL maintenance status `maintained'.
    
    The Current Maintainer of this work is Ruixi Zhang.
    
    This work consists of the files lstfiracode.sty,
                                    lstfiracode.tex,
                                    README.md (this file)
              and the derived file  lstfiracode.pdf.