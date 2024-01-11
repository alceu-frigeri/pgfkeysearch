pgfkeysearch
==========

This package offers a way to find keys in a given path 'recursively', unlike pgfkeysvalueof.

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*)
and pgfkeys.


## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/pgfkeysearch/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/pgfkeysearch

-------------
Copyright 2023-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consist of the files

* pgfkeysearch.sty
    - the package itself

* README.md  (this file)
    - quick introduction

* pgfkeysearch.tex
    - pakcage documentation
* pgfkeysearch.pdf
    - documentation in PDF format
    
-------------

## Changelog

* Version 1.2 (this)
    - More typos.
    - added two command aliases, see documentation.

* Version 1.1
    - More typos.
    - renamed some internal variables to better follow the expl3 recommendations. 
    - exposing the Expl3 commands.

* Version 1.0
    - Initial setup.
