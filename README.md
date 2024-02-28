# LaTeX Workshop

This repository contains materials for _LaTeX for the Humanities_, a two-hour introductory workshop for LaTeX aimed at students and staff members working at the Faculty of Humanities of Utrecht University.

There are two main `.tex` files in this repository.

* `latex-workshop-humanities.tex` is used to create the handout with exercises and in-depth explanations. All participants should get a copy of the resulting PDF before the start of the workshop. After the workshop they should receive a copy of the source code of the handout, so they can check the answers to the exercises.

* `latex-humanities-beamer.tex` contains the source code for the (PPT-like) slideshow used by the lecturer during the workshop.

To fully compile these, you need the XeLaTeX compiler and the `biber` tool for the bibliography. In general, you should run XeLaTeX once, followed by one run of `biber` and two consecutive runs of XeLaTeX.

For VSCode users using [James Yu's LaTeX extension](vscode:extension/James-Yu.latex-workshop) (recommended), a `settings.json` has been provided that prepares the necessary 'recipes'.