TEMPLATE LATEX THESE
=====================

* Ceci est un template 
* Il est en LaTex
* Ça te permet d'écrire ta thèse 
* Comme ça, t'écris des trucs en LaTex avec ce template et pouf t'as une thèse. 



Utilisation 
-----------

* copier-coller le fichier "content_example" en "content" pour linker les bons fichiers. Dans le main, (dé) commenter les lignes correspondantes. 
* idem pour la biblio et les annexes 
* Si vous avez des idées d'amélioration, surtout n'hésitez pas à en faire profiter tout le monde ! (si vous ne maîtrisez pas git, envoyez vos suggestions à quelqu'un qui saura le mettre à jour)


Tips généraux 
--------------

* Pour alléger un pdf un peu trop gros parce que t'as déconné sur les figures : gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/prepress -dNOPAUSE -dQUIET -dBATCH -dPrinted=false -sOutputFile=main_light.pdf main.pdf

* Pour trouver un symbole LaTex : http://detexify.kirelabs.org/classify.html

* de la doc 
    * bonnes pratiques : https://www.lrde.epita.fr/~didier/research/publications/papers/verna.11.tug.pdf 
    * pgfplot : https://ctan.gutenberg.eu.org/graphics/pgf/contrib/pgfplots/doc/pgfplots.pdf
    * tikz : https://tikz.dev/


