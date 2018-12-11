# Geomapping the Hebrew Bible

This repo contains Jupyter Notebooks created for mapping the Biblical locations as mapped in the [OpenBible](https://www.openbible.info/geo/) project with the topological names of the [ETCBC database](https://github.com/ETCBC/bhsa) of the Hebrew Bible. The OpenBible data is licensed under a Creative Commons Attribution licence.

## Mapping the Hebrew Bible

The mapping of the OpenData dataset and the ETCBC database is straight-forward. Each location is treated as a lexeme mapped against the glosses of the ETCBC database. Only identical glosses are used.

The mapping could be improved by accounting for varying vowels in otherwise identical words. It would be interesting to experiment with other variations of regular expression.

The mapping is coded in Python and the resulting dataset is exported as two [text-fabric](https://dans-labs.github.io/text-fabric/) feature sets: latitude ```lat``` and longitude ```long```.
