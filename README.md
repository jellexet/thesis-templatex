# LaTeX Thesis Template

`thesis_templatex` is the official template for theses to be written in LaTeX, which is made available for the graduation at the Robotics Laboratory of the Department of Electrical, Computer and Biomedical Engineering, University of Pavia.
The name of the repository reflects its purpose: `thesis temp-latex` :-D

# Notes on installation

MacOS user **MUST** install the rsvg-convert software in order to convert svg to pdf.

How to install rsvg-convert run on a terminal:
```
brew install librsvg
```

# Building the pdf

If you use the terminal and have all the tools installed, you can run

```
make all
```

to generate the pdf file.

It automatically converts the figures into supported formats, and handles the correct generation of the bibliography.
It uses external tools to convert the following file formats:

* `.gif` with [ImageMagick](https://imagemagick.org/index.php) `convert`
* `.dia` with [Dia](http://dia-installer.de/download/linux.html.en)
* `.fig` with [XFig](https://www.xfig.org/)
* `.svg` with [Inkscape](https://inkscape.org/)

# Credits

* Tullio Facchinetti
* Guido Benetti
* Gianluca Roveda
