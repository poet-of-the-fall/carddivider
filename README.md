# Dominion Card Divider

This card dividers can be used if you plan to pack your Dominion sets into a box or suitcase and want to stack them.

It is based on the works of Eiko Wagenknecht ([visit his website](http://www.phenx.de/dominion-kartentrenner/)) and contains all of his card dividers now set in LaTeX as well as all of the current sets offered by Rio Grande Games with the instructions offered on their [website](http://www.dominion-welt.de/support/downloads/).

To compile the card dividers you need a Latex distribution. To read more about this, you can start [here](https://www.latex-project.org/get/#distributions).

**Feel free to add further card sets, editions, languages or formats or correct some errors or typos. To do so fork the project and open a pull request or use the issues section if you aren't familiar with LaTex and/or Github.**

## Compiling the PDFs

You can use TexStudio or some other editor to edit the files and compile the PDFs. Remember to change your standard compiler to *lualatex* if you compile the PDFs with your editor.

For this project I gave [Visual Studio Code](https://code.visualstudio.com) a try. I used the *Latex Workshop* extension for the LaTeX stuff (it auto compiles the project on saving with the given settings in the root file head comment). For spell checking I installed *Code Spell Checker* and the *German - Code Spell Checker* extensions and updated the ```.vscode/settings.json``` accordingly.

If you only need some of the sets in your PDF just comment out the sets you don't need and compile exactly the version you need.

## Portrait or Landscape

To switch between the portrait and landscape mode take a look at ```cards.tex``` in the root folder. Watch for these lines:

```latex
% Draw cards in portrait format
\input{format/tikzcardsportrait.tex}
% Draw cards in landscape format
%\input{format/tikzcardslandscape.tex}
```

Uncomment the version you want to use and comment out the other one.