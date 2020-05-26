# PDF reader using python curses 

PDFcurse is a terminal text oriented reader for
[PDF](https://en.wikipedia.org/wiki/PDF)
documents
using Python _curses_ to provide a user interface
similar to
[Evince](https://en.wikipedia.org/wiki/Evince).
In this initial incarnation,
it wraps around
[pdftotext](https://en.wikipedia.org/wiki/Pdftotext),
and is somewhat redundant over
the _less_ command in Linux systems.

What it does additionally
like
[Evince](https://en.wikipedia.org/wiki/Evince)
is watching the PDF file,
so PDFcurse can be used say in a 
[Tmux](https://en.wikipedia.org/wiki/Tmux)
pane
while working on its 
[LaTeX](https://en.wikipedia.org/wiki/LaTeX)
source in another pane.

One thing I did do differently,
just to think outside the Vim box,
is to use left hand keys in the QWERTY layout,
mainly because 35 years of Vi and Vim editing,
and the mouse, and driving,
and the 700+ techniques of
[kenpo](https://en.wikipedia.org/wiki/American_Kenpo)
and almost all the weapon forms in
[martial arts](https://en.wikipedia.org/wiki/Chinese_martial_arts)
have worn down out my right side. 


## Installation

TBD


## How to use

Just run
```
pdfcurse file
```

And use:

| key | mnemonic | command |
| --- | --- | --- |
| a | aft | move backward by one page |
| f | fore | move forward by one page |
| g | go to | pops a text box for page number and takes you there (programmer's fantasy!) |
| e | east | pan to the right |
| w | west | pan to the left |
| v | vertical (down) | pan down by 5 lines |
| r | reverse vertical (up) | pan up by 5 lines |
| c | continuous mode (toggle) | self-explanatory |

