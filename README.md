# Geomapping the Hebrew Bible

This repo contains Jupyter Notebooks created for mapping the Biblical locations as mapped in the [OpenBible](https://www.openbible.info/geo/) project with the topological names of the [ETCBC database](https://github.com/ETCBC/bhsa) of the Hebrew Bible. The OpenBible data is licensed under a Creative Commons Attribution licence.

## Mapping the Hebrew Bible

The mapping of the OpenData dataset and the ETCBC database is straight-forward. Each location is treated as a lexeme mapped against the glosses of the ETCBC database. Only identical glosses are used.

The mapping could be improved by accounting for varying vowels in otherwise identical words. It would be interesting to experiment with other variations of regular expression.

The mapping is coded in Python and the resulting dataset is exported as two [text-fabric](https://dans-labs.github.io/text-fabric/) feature sets: latitude ```lat``` and longitude ```long```.

## Licence
This work is licensed under a Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). That means:

* You may download the data and use it: process, copy, modify;
* You may use the data to create new software applications;
* You may use the data for research and publish any amount of results;
* When you publish this data or results you obtained from them, you have to comply with the following: [![DOI](https://zenodo.org/badge/161319412.svg)](https://zenodo.org/badge/latestdoi/161319412)
  * give proper attribution to the data when you use it in new applications, by citing this persistent identifier:
  * do not use the data for commercial applications without consent.
