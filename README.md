
## Demo
<img src="/Poster_Template_for_CUHK.png" width="400">
<img src="/Poster_Template_for_CUHK_2.png" width="800">

## Environment
* [Overleaf](https://www.overleaf.com/project) (recommended)

## Usage
* ``poster.tex``: the entry point of the LaTeX project. 
* ``poster.bib``: bibliography file.
* ``beamercolorthemecuhk.sty``: style file from [uchicago-poster](https://github.com/k4rtik/uchicago-poster). You can modified the color in this file.
* ``logo``: folder storing CUHK logo

## Quick Start
Here are some intructions to help you use this template.
* Modify the paper size with ``width`` and ``heigh`` in ``\usepackage[orientation=portrait, size=custom,width=84,height=42,scale=0.6]``;
* When you modify the paper size, adjust the ``height`` in  ``\logoleft{\includegraphics[height=4cm]{logos/CUHK-Logo.png}}`` to get a better layout;
* Normally, the poster will have 2 or 3 colomns, here are some suggestions:
  * for 2 colomns, ``\setlength{\sepwidth}{0.025\paperwidth}`` and  ``\setlength{\colwidth}{0.45\paperwidth} ``
  * for 3 colomns, ``\setlength{\sepwidth}{0.01\paperwidth}`` and  ``\setlength{\colwidth}{0.32\paperwidth}``


  

## Reference 
[https://github.com/k4rtik/uchicago-poster](https://github.com/k4rtik/uchicago-poster)

[https://www.overleaf.com/latex/templates/poster-template-for-nottingham-centre-for-geomechanics/tmpkbjdnxwrr](https://www.overleaf.com/latex/templates/poster-template-for-nottingham-centre-for-geomechanics/tmpkbjdnxwrr)
