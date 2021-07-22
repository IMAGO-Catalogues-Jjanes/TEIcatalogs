# TEI Catalogs Production

This repository contains TEI files of 19th and 20th exhibition catalogs. 

## Production
Those files were created thanks to this pipeline:

<p class="float" align="center">
<img src="./pipeline.png">
  </p>

Segmentation and transcription were done in eScriptorium, using models trained with Kraken on datasets from [here](https://github.com/Juliettejns/cataloguesSegmentationOCR) and [here](https://github.com/Juliettejns/cataloguesOCR).<br/>
Python data extraction which transformed the ALTO4 files extracted from eScriptorium to TEI files is accessible [here](https://github.com/Juliettejns/extractionCatalogs).

Manual correction is done between each step of the pipeline.
<br/>Since the Layout analysis has been corrected for each catalogs, ALTO4 files extracted from eScriptorium can then be used to train a more efficient segmentation model.

## TEI files

The TEI files were built in order to stick to the [ODD](https://github.com/carolinecorbieres/ArtlasCatalogues/blob/master/5_ImproveGROBIDoutput/ODD/ODD_VisualContagions.xml) done by Caroline Corbières.

## Repository
This repository presents, for each catalog, images, alto4 files extracted from eScriptorium, TEI and csv file.

## Credits
This repository is developed by Juliette Janes, intern of the [Artl@s](https://artlas.huma-num.fr/fr/) project, with the help of Simon Gabay under the supervision of Béatrice Joyeux-Prunel.

## Licence
Images from catalogs published prior 1920 and transcriptions are CC-BY. </br>
The other images are extracts of catalogs published after 1920 and are the intellectual property of their productor.</br>
![68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792f322e302f38387833312e706e67](https://user-images.githubusercontent.com/56683417/115525743-a78d2400-a28f-11eb-8e45-4b6e3265a527.png)

## Cite this repository
Juliette Janes, Simon Gabay, Béatrice Joyeux-Prunel, _TEICatalogs production_, 2021, Paris: ENS Paris https://github.com/Juliettejns/TEIcatalogs/

## Contacts
If you have any questions or remarks, please contact juliette.janes@chartes.psl.eu and simon.gabay@unige.ch.
