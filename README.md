# BibTeX-Database
A personal database for quick addition of citations.

This is not an interface to OverLeaf but only for local usage. 

## A Basic Example:

1\. .bib file (sample.bib)

```shell
@article{smith2024,
  author = {John Smith},
  title = {An Interesting Study},
  journal = {Journal of Interesting Results},
  year = {2024},
  volume = {42},
  pages = {1--10}
}
```


2\. LaTeX Document

```shell
\documentclass{article}
\begin{document}

This is a reference to a study \cite{smith2024}.

\bibliographystyle{plain}
\bibliography{sample}

\end{document}
```
