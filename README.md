Designing Internal Synchronous Software API
===========================================

This guide is intended to help you design an internal synchronous API between software components in the service.
It contains a set of guidelines and recommendations that should be followed when designing an API
in form of design approaches and related design patterns.

The guide is divided into following sections:

1. Introduction
2. Requirements
3. Domain Analysis
4. Singleton Interface Method
5. Method Multiplication
6. Bulk Method
7. Default Values
8. Parameter Object
9. API Strategies
10. Model-Driven API
11. Summary

Commands used for generation of PDF document from LaTeX sources:

    cd src
    pdflatex -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=~/Documents main.tex

The generated PDF document is available on the `~/Documents/main.pdf.` path.

---
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg