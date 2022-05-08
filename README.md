# PhD thesis source code

This is the full source code (and a compiled PDF) of my PhD thesis, submitted in 2021. With some modifications, this was adapted from the template originally created by Dr Laura Driessen. Her "readme" notes are below.

[A clean template of this thesis can be found here.](https://github.com/crispinagar/thesis-template)

Crispin Agar, 2022-05-08



## Laura's Introduction

This is a University of Manchester template for a PhD thesis created by Laura Driessen (www.AstroLaura.com)

By using this template you are agreeing to check *yourself* whether it meets the requirements of the University of Manchester for PhD thesis submission. The guidelines for PhD thesis presentation can be found here: https://www.bmh.manchester.ac.uk/doctoral-academy/your-phd/thesis-submission/presentation-regulations/

Make sure you change everything that needs changing, like your name (must include the initial of your middle name), your supervisor's name, the colour scheme, the Declaration of Authorship, thesis title etc.

The UoM guidelines require that any blank page has the words "Blank page" on it, so I made a command for that. If you'd like to insert a blank page that has "Blank page" smack bang in the middle, just use `\UoMBlankPage`

The guidelines are also a bit weird about numbering, and font is important.

YOU WILL NEED TO CHANGE THE DECLARATION OF AUTHORSHIP PAGE! This is because the declarations depends on whether (and which) bits are published etc, so will vary thesis by thesis.

Not all of the preamble pages are required. You don't have to have lists of symbols, physical constants, abbreviations, popular abstract, preface etc. Read the guidelines to check which ones can be removed and what order they have to be in.

You can use fontspec to set up all the fonts, eg:
```latex
>>> \usepackage{fontspec}
>>> \setmainfont{Bitstream Vera Sans}
```
before `\begin{document}`, but then you need to go into your overleaf settings and change the LaTeX engine to XeLaTeX or LuaLaTeX. I have these lines commented out currently, and instead I'm using `\usepackage{mathpazo}` which is Palatino font.

And no, those are not the colours I used for my thesis template. I made them particularly garish so that you would choose your own colours (and there's no requirement for your thesis colours to be ugly or black and white, I checked! Colours are good!)! There are some great colour picking tools online, seriously good:
https://www.canva.com/color-palette/
https://coolors.co/
https://htmlcolorcodes.com/color-chart/
and if you need to ever convert from RGB to HEX (or vice versa):
https://www.webfx.com/web-design/hex-to-rgb/

Good luck!  Please let me know if you come across any issues and I'll update my master template :D