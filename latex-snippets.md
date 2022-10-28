---
layout: default
title: LaTeX Snippets
permalink: /latex
---

# Latex Snippets

## TexStudio Specific
Magic comment
`% !TeX program = xelatex`
forces TexStudio to render with xelatex

# Itemize environment
Use below to keep items a bit closer than default
```latex
\begin{itemize} \itemsep1pt \parskip0pt \parsep0pt
	\item Education Leave Germany
\end{itemize}
```
# Description environment
```latex
\begin{description}[leftmargin=0.25cm]
	\item[First Item] is a representation of the \emph{reporting} lines that are created and maintained ...
	\item[Second Item] is a representation of the structure used in Finance, showing which segment pays ...
\end{description}
```
Defining the left margin requires the `enumitem` package.
# Packages
## MenuKeys
Enable creation of pretty menu-/key-guides

CTAN: [menukeys](https://www.ctan.org/pkg/menukeys)

```latex
\usepackage{menukeys} % Enable creation of pretty menu-guides

% Examples

\menu{Extras > Settings > Rulers}
\keys{Alt + L}
\directory{C:/FILES/DOCS}
```

## Other Packages
<table>
	<tr>
		<td><b>Package</b></td>
		<td><b>CTAN</b></td>
		<td><b>Line</b></td>
		<td><b>Description</b></td>
	</tr>
	</hr>
	<tr>
		<td>Multirow</td>
		<td><a href="https://www.ctan.org/pkg/multirow">multirow</a></td>
		<td>\usepackage{multirow}</td>
		<td>Allows cells in tables to span multiple rows.</td>
	</tr>
	<tr>
		<td>Enumitem</td>
		<td><a href="https://www.ctan.org/pkg/enumitem">enumitem</a></td>
		<td>\usepackage{enumitem}</td>
		<td>Enable changing the indentation for text in description environments.</td>
	</tr>
	<tr>
		<td>Parskip</td>
		<td><a href="https://ctan.org/pkg/parskip">parskip</a></td>
		<td>\usepackage{parskip}</td>
		<td>Removes automatic indentation for paragraphs.</td>
	</tr>
	<tr>
		<td>booktabs</td>
		<td><a href="https://ctan.org/pkg/booktabs">booktabs</a></td>
		<td>\usepackage{booktabs}</td>
		<td>Improves tables.</td>
	</tr>
</table>
