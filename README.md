# Dominion Card Divider

Based on the works of Eiko Wagenknecht ([visit his website](http://www.phenx.de/dominion-kartentrenner/)).

To compile the card devider you need a Latex distribution. To reed more about this, you can start [here](https://www.latex-project.org/get/#distributions).

Feel free to add further card sets, editions or languages.

## Portrait or Landscape 

To switch between the portrait and landscape mode take a look at ```cards.tex``` in the root folder. Look for these lines:

```latex
%   Draw cards in portrait format
\input{format/tikzcardsportrait.tex}
%   Draw cards in landscape format
%\input{format/tikzcardslandscape.tex}
```

Uncomment the version you wnat to use and comment out the other one.