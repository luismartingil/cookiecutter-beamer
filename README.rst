cookiecutter-beamer
===================

Cookiecutter template for a LaTeX Beamer presentation.

.. image:: https://raw.github.com/audreyr/cookiecutter/aa309b73bdc974788ba265d843a65bb94c2e608e/cookiecutter_medium.png


Installation
------------

- Debian:

    # Installing some dependencies
    sudo apt-get install texlive-base texlive-fonts-recommended texlive-latex-base texlive-latex-recommended texify multex-bin tetex-frogg  tex-gyre  texlive-xetex texlive-pictures texlive-luatex texlive-bibtex-extra  texlive-extra-utils  texlive-font-utils texlive-fonts-extra  texlive-formats-extra texlive-generic-extra texlive-games  texlive-plain-extra texlive-latex-extra texlive-science texlive-base texlive-fonts-recommended texlive-latex-base ttf-dejavu-core ttf-gfs-* ttf-dejavu ttf-liberation ttf-bitstream-vera

    sudo cp *.sty /usr/share/texmf-texlive/tex/latex/

    sudo texhash

    # Install python Pygments
    sudo pip install Pygments

    # Run the pdflatex command
    make

Author
------

 - Luis Martin Gil - www.luismartingil.com