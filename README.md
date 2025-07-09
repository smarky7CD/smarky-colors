# smarky-colors

My custom $\LaTeX$ color scheme.

- The page background is ![#fffff8](https://placehold.co/15x15/fffff8/fffff8.png) `#fffff8`.
- The main text color is ![#23395b](https://placehold.co/15x15/23395b/23395b.png) `#23395b`.
- The accent color (section headings, links, citations, `\emph`, etc.) is ![#a88f2a](https://placehold.co/15x15/a88f2a/a88f2a.png) `#a88f2a`

The font is [Libertinus Serif](https://github.com/alerque/libertinus) and the . These can be commented out in the `.sty` file. 

## To Use 

Simply include `smarky-colors.sty` in your $\LaTeX$ project directory and then include in your project preamble. 

```LaTeX
\documentclass{article}
\usepackage{smarky-colors}

\begin{document}

\section{Introduction}
...
\end{document}
```