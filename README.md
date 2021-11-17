NAIST Thesis Template (Division of Information Science)
========================================================

The format specification for Master's/Doctoral theses in NAIST IS division was updated at the end of the FY 2020.
This repository offers an unofficial LaTeX template.

### Design philosopy

#### Make it as simple as possible
I implemented nothing irrelevant to the format specification.
I know you want to use packages or configurations you choose on your own, and I want to avoid any conflicts between your settings and my template.

#### Make it as easy as possible to use
You only need to `\input` one `.tex` file and one line just after `\begin{document}`.
All the required configurations (e.g., your name, thesis title, etc.) are packed in the upper half of the template file.

### Usage
Compiling the source below would result in a [PDF like this](https://github.com/iTakeshi/naist-thesis.tex/blob/master/main.pdf).
```tex
% main.tex

\documentclass[12pt]{report}

\input{naist-thesis}  % configure the variables in naist-thesis.tex

\begin{document}
\NaistFrontPages

\chapter{Introduction}

\end{document}
```

### Bug reports
I only tested this template using TexLive 2021 and XeLaTeX under a Linux system.
Please do not hesitate post issues/pull requests if you encounter any bugs and troubles using the template, or you have any ideas to improve it.
Especially, I really appreciate it if someone could send a pull request to make this template compatible with Japanese theses.
日本語化のためのPull requestをお待ちしております。

### Acknowledgments
I would like to thank @kmiya for creating the former version of the template (https://github.com/kmiya/naist-thesis-tmpl-en).
