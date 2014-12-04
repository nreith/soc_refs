BibTeX files of use to political sociologists
=======

> *"Imitation is the sincerest of flattery."*
>
> ~ Charles Caleb Colton, 1820

This github repository, as much of my work, owes a direct debt of gratitude to [Professor Kieran J. Healy](https://github.com/kjhealy/socbibs#bibtex-files-of-use-to-sociologists) Duke University. Though I have never met him, his public Sociology has offered endless inspiration for my evolution toward Sociological Geekdom.

*	**Author:** Nicholas E. Reith
*	**Affiliation:** Sociology Department, The University of Texas at Austin
*	**Date:** 2014-12-04
*	**Keywords:** sociology, bibtex, bib, political sociology, revolution, conflict, protest, religious and ethnic social movements, networks, contentious politics, social capital, pro-social behavior, altruism, generosity


Summary

The contents of my ../texmf/bibtex/bib directory. 'socbib.bib' is a consolidated bibtex file created by merging a number of bibtex files I've compiled over the years. The content reflects citations in my own work.

The bibtool-rsc folder contains some elementary resource files I use while converting, sorting, and normalizing the bib file using the bibtool utility. To properly sort the bib file after adding and entry, do

bibtool -s -i socbib.bib -o socbib.bib
bibtool -r bibtool-rsc/crossref.rsc -i socbib.bib -o socbib.bib

The first command sorts the entries alphabetically. The second puts crossref'd items (e.g. book chapters) at the beginning, so that bibtex can find their parent entries (e.g. edited volumes) properly.
