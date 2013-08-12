GTALUG's Bylaws
===============

Generate Bylaws
---------------

I am generating the bylaws with [Pandoc](http://johnmacfarlane.net/pandoc/).

### HTML

	pandoc -N -c gtalug.css GTALUG-Bylaw.mdown -o GTALUG-Bylaw.html
	pandoc -N -c gtalug.css GTALUG-Bylaw-Number-1/*.markdown -o GTALUG-Bylaw-Number-1.html

### PDF

	pandoc -N -c gtalug.css GTALUG-Bylaw.mdown -o GTALUG-Bylaw.pdf
	pandoc -N -c gtalug.css GTALUG-Bylaw-Number-1/*.markdown -o GTALUG-Bylaw-Number-1.pdf
