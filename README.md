## Slides template

Requires:

* `metropolis` beamer theme
* Avenir Next font
* Inconsolata font 
* `bayesnet` tikz library (if you want the diagrams)

Metropolis is available from CTAN but may not be pre-installed on a texlive based system like Mactex.
So install it from [there][1]. If you're using [Mactex][2] the `TeX Live Utility` will do it.  

If you have no graphical installer, follow the instructions in the CTAN entry and put in your 
*special place*.  (Don't get too excited, on a Mac that's as a subfolder of `~/Library/tex/latex/`, 
which you may have to create first).

Avenir Next comes with OSX and is the finest sans serif I know for slides.  It's an updated version of [Frutiger's Finest][3] and the official font of the Eurovision Song Contest.  But don't let that put you off.  You could replace with something less round, like Helvetica, but I'll judge you.

Inconsolata is my favourite font for code snippets, or Monaco.  But this one seems to run better with Avenir. You can find a copy [here][4].

You can find the `bayesnet` library for Tikz [here][5].

Now compile the whole thing with `XeLaTeX` or similar, else all those lovely fonts won't work.



*Will Lowe, June 2016*

[1]:	https://www.ctan.org/pkg/beamertheme-metropolis?lang=en
[2]:	https://tug.org/mactex/
[3]:	https://en.wikipedia.org/wiki/Avenir_(typeface)
[4]:	http://www.levien.com/type/myfonts/inconsolata.html
[5]:	https://github.com/jluttine/tikz-bayesnet
