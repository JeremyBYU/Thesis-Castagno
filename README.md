# My Thesis

This is contains all the source files for my completed thesis.

## Possible Outline


## Note for self

### Figures TOC

You can have custom short captions to be displayed in the table of contents. Simply put the caption in the optional brackets for the `\caption` command.

```tex
\documentclass[11pt]{article}
\usepackage{blindtext}
\begin{document}
 
\tableofcontents
\listoffigures
 
\section{Dummy section 1}
\begin{figure}[ht]
\begin{center}
\rule{0.5\linewidth}{0.35\linewidth}
\caption[Long caption figure]{Really long cpation \blindtext}
\label{fig:dum1}
\end{center}
\end{figure}
 
\end{document}
```

### Acronyms

Use an acronym for the first time with: `\acf{sUAS}`. Subsequent used can then be `\ac{sUAS}`. All acryonyms are defined in `misc\acronym_list.tex`

