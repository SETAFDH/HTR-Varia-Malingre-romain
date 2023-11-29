# OCR-Malingre

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

Ce dépôt comprend les données OCR des textes suivants : les ouvrages attribués au poète réformé M. Malingre (c.1500-1572) et d'autres ouvrages utiles à étudier son oeuvre. La liste des textes avec plus de détails se trouve dans le tableau CSV du dépôt.

Les ouvrages de M. Malingre imprimés par Pierre de Vingle et Jean Michel se trouvent également dans les dépots suivants : https://github.com/SETAFDH/HTR-SETAF-Pierre-de-Vingle et https://github.com/SETAFDH/HTR-SETAF-Jean-Michel.


## Financeur

Ce projet est financé par le Fonds national suisse (FNS) dans le cadre du projet SETAF.

- Site du projet SETAF : https://www.unige.ch/setaf
- GitHub du projet SETAF : https://github.com/SETAFDH


## Licence

Les transcriptions sont [CC-BY](https://creativecommons.org/licenses/by/4.0), et les images suivent les règles de différentes bibliothèques numériques :
- e-rara : https://www.e-rara.ch/wiki/termsOfUse?lang=en
- Österreichische Nationalbibliothek : https://www.onb.ac.at/en/use


## Données

Les données se trouvent au chemin ‘./data//.xml‘ et sont au format ALTO. Elles suivent les normes de segmentation SegmOnto (https://segmonto.github.io) et sont cataloguées sur HTR-United (https://htr-united.github.io). Les fichiers sont corrigés manuellement : la qualité de la segmentation des pages et de la transcription produite par l'OCR est indiqué dans le tableau CSV du dépôt ("gold" ou "en cours").

Le contrôle de la transcription produite par l'OCR se base sur un guide redigé par l'équipe du projet SETAF : Solfrini et al., Guide de transcription pour les imprimés français du XVIe siècle en caractères gothiques, Version A, 2023, https://hal.science/hal-04281804.


## Infrastructure

Les données pour l'OCR sont produites à l'aide de l’instance genevoise FoNDUE (https://www.unige.ch/lettres/humanites-numeriques/recherche/projets-de-la-chaire/fondue) d'eScriptorium (https://gitlab.com/scripta/escriptorium).

Les calculs sont effectués à l'Université de Genève en utilisant le service Baobab HPC : https://www.unige.ch/eresearch/fr/services/hpc/.
  

## Citer le dépôt

- Version `1.0`: Sonia Solfrini, _Données OCR des ouvrages de M. Malingre et des textes utiles à étudier son oeuvre_, version `1.0`, Genève, université de Genève, 2023, https://github.com/SETAFDH/OCR-Malingre.

```bibtex
@misc{solfrini_ocr_malingre_2023,
  author={Solfrini, Sonia},
  title={Données OCR des ouvrages de M. Malingre et des textes utiles à étudier son oeuvre},
  version={1.0},
  address={Genève},
  publisher={université de Genève},
  year={2023},
  url={https://github.com/SETAFDH/OCR-Malingre},
}
```
