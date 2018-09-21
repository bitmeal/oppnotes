# Open-Pdf-Presenter Notes

Latex-Beamer package `oppnotes.sty` to make notes in XML format understood by *open pdf presenter*. File containing notes will be `\jobname.xml`



## Usage

In frame use `\oppnote{...}`, linebreak in notes supported.

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

