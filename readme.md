# FOP-BOT LaTeX Package
## Installation
Place the .sty File in the same directory as your .tex file and insert the line:
```tex
\usepackage{FOPBot}
```
in the Preamble of your document.
## Usage
The Package defines the Environment `FOPBotWorld`:
```tex
\begin{FOPBotWorld}{<width>}{<height>}
    % Your Code here
\end{FOPBotWorld}
```
Each tile is a node with the common anchors, which is acessible by the name (n-\<X>-\<Y>).  
To place Coins use the command:
```tex
\putcoin{<X>}{<Y>}{<Amount>}
```
Robots are defined as Pics, and have an option for color. See the example for more details.
## Planned Features
- Scaling
- Better Wall Creation
- More Settings
## Author
&copy; [Ruben Deisenroth](https://github.com/Rdeisenroth), November 2020