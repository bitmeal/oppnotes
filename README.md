# oppnotes
Latex-Beamer package `oppnotes.sty` to make notes in XML format understood by [*open-pdf-presenter*](https://code.google.com/archive/p/open-pdf-presenter/). File containing notes will be output as `\jobname.xml`



## Usage

In frame environment use `\oppnote{...}`; linebreak in notes supported.

```latex
\usepackage{oppnotes}
...

\begin{frame}
	...
	\oppnote{
        Your note\\
        text
	}
\end{frame}
```

