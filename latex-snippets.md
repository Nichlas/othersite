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
| Package | CTAN | Line |  Description |
| -- | --- | --- | --- |
| Multirow | [multirow](https://www.ctan.org/pkg/multirow) | `\usepackage{multirow}` | Allows cells in tables to span multiple rows. |
| Enumitem| [enumitem](https://www.ctan.org/pkg/enumitem) | `\usepackage{enumitem}` | Enable changing the indentation for text in description environments |
| Parskip | [parskip](https://ctan.org/pkg/parskip) | `\usepackage{parskip}` | Removes automatic indentation for paragraphs |
| booktabs | [booktabs](https://ctan.org/pkg/booktabs) | `\usepackage{booktabs}` | Improves tables |

