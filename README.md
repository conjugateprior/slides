## Slide templates

### Requirements:

* Latex (even if you're going to use rmarkdown)
* `metropolis` beamer theme
* Avenir Next font
* Inconsolata font 
* `bayesnet` tikz library (if you want the diagrams in the examples to work)
* RStudio (or R with rmarkdown installed) for the rmd version

Metropolis is available from CTAN but may not be pre-installed on a texlive 
based system like Mactex. If you're using [Mactex][2] the `TeX Live Utility` 
will do it.  

If you have no graphical installer, follow the instructions in 
the [CTAN entry][1] and put in your 
*special place*.  (Don't get too excited, on a Mac that's any subfolder of `~/Library/texmf/tex/latex/`, which you may have to create first).

Avenir Next comes with OSX and is the finest sans serif I know for slides.  
It's an updated version of [Frutiger's Finest][3] and the official font of the Eurovision Song Contest.  But don't let that put you off.  You could replace with something less round, like Helvetica, but I'll judge you.

Inconsolata is my favourite font for code snippets, or Monaco.  But this one seems to run better with Avenir. You can find a copy [here][4].

You can find the `bayesnet` library for Tikz [here][5].

### Usage:

For latex users: `tex/slides.tex` compiles in your usual latex environment
provided you use XeLaTeX and have all the requirements noted above.

For rmarkdown users: `rmd/slides.rmd` compiles when you put it in an RStudio
window and press the 'knit' button.  If anything goes wrong you then you are 
probably missing an latex requirement.

### Notes:

`rmd/rmd_teaching_slides.tex` is a template that you can adjust if you don't 
some detail of my slide style.  It's mostly just latex.  To adjust slide content
just write markdown and/or R in `rmd/slides.rmd`.

Once you've got a template you like, it's probably sensible to move it to
`~/.pandoc/templates` so that all your rmd files can refer to it in the same
way `slides.rmd` does.


*Will Lowe, June 2018*

[1]:	https://www.ctan.org/pkg/beamertheme-metropolis?lang=en
[2]:	https://tug.org/mactex/
[3]:	https://en.wikipedia.org/wiki/Avenir_(typeface)
[4]:	http://www.levien.com/type/myfonts/inconsolata.html
[5]:	https://github.com/jluttine/tikz-bayesnet
