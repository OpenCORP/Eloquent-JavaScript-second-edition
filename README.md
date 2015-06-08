# Eloquent JavaScript

Estos son, los codigos de fuentes utilizados para construir la segunda edición de Elocuente
 JavaScript (http://eloquentjavascript.net).

Los Comentarios son bienvenidos, en forma de problemas y pull requests.

## Building

    npm install --production
    apt-get install asciidoc inkscape
    make html

Para OSX, usted puede utilizar port o brew para instalar el paquete asciidoc.

Para generar el archivo PDF:

    apt-get install texlive texlive-xetex texlive-fonts-extra
    make book.pdf

Para generar el libro ePub:

    make book.epub


