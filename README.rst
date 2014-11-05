cookiecutter-beamer
===================

Cookiecutter template for a LaTeX Beamer presentation.

Installation
------------

Install latex dependencies and Pygments for source code highlight.

- Debian:

    # Installing some dependencies

    sudo apt-get install texlive-base texlive-fonts-recommended texlive-latex-base texlive-latex-recommended texify multex-bin tetex-frogg  tex-gyre  texlive-xetex texlive-pictures texlive-luatex texlive-bibtex-extra  texlive-extra-utils  texlive-font-utils texlive-fonts-extra  texlive-formats-extra texlive-generic-extra texlive-games  texlive-plain-extra texlive-latex-extra texlive-science texlive-base texlive-fonts-recommended texlive-latex-base ttf-dejavu-core ttf-gfs-* ttf-dejavu ttf-liberation ttf-bitstream-vera

    sudo cp *.sty /usr/share/texmf-texlive/tex/latex/

    sudo texhash

    # Install python Pygments for minted source code

    sudo pip install Pygments

    # Run the pdflatex command

    make


Output
------

Check this `pdf file <bin/main.pdf>`_

- Some screenshots:

.. image:: bin/main000.png
.. image:: bin/main001.png
.. image:: bin/main002.png
.. image:: bin/main003.png
.. image:: bin/main004.png
.. image:: bin/main005.png
.. image:: bin/main006.png
.. image:: bin/main007.png
.. image:: bin/main008.png