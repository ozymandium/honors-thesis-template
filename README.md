honors-thesis-template
======================
A starting point for writing your Auburn University Honors Thesis using LaTeX


If you're experienced with TeX (specifically LaTeX here), the style file is
located in ./thesis/sty/auhonors.sty  
It is an amalgamation of code from various files (some about a decade old as of this writing), but worked well when I wrote my honors thesis, so consider yourself warned.

If you don't have any prior experience, there is an abundance of examples out on the interwebs. [This SE site](http://tex.stackexchange.com/) and [this site](http://www.texample.net/) are two great places to start.


### Headings ###
If you don't want to use the all caps convention, you need to remove `\sc` from heading titles in the style file.


### Windows ###
I have put all the figures into a `figs` folder, so if you're using Windows you will want to do one of the following:   

- combine the whole thing into one folder  
- change `/` in the file paths for the figures to `\`  

Either way, as a habitual user of Microsoft products, you will want to:

- Stop for a second  
- Reevaluate the life decsions which have led you to this point
- Have a good cry


### Typesettings ###

`thesis.tex` was compiled with pdfTeX 3.1415926-2.4-1.40.13 (TeX Live 2012/Debian)

There shouldn't be any problems with other methods.