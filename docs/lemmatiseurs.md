---
layout: default
title: Lemmatiseurs, paramètres, outils
nav_order: 4
---

# Lemmatiseurs, paramètres, outils
{: .no_toc }

<details open markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

La lemmatisation peut s’effectuer à l’aide des différents outils de lemmatisation et s’appuyer sur différents jeux de paramètres. Cette présentation porte un regard particulier à quelques lemmatiseurs et jeux de paramètres utiles dans le travail avec des textes médiévaux. 

## OMNIA
{: .mb-3 }

OMNIA a été élaboré pour être implementé au logiciel [TreeTagger](https://www.cis.lmu.de/~schmid/tools/TreeTagger/){:target="_blank"}, développé pour le marquage morphosyntaxique (_POS – Part of Speech_), mais qui permet également la lemmatisation. OMNIA propose à la fois les paramètres nécessaires à son utilisation avec des textes en latin médiéval, et les fichiers permettant de recréer ces paramètres.

Page web: [OMNIA](https://glossaria.eu/lemmatisation/#page-content){:target="_blank"}

---

## Collatinus
{: .mb-3 }

Collatinus est à la fois un lemmatiseur et un analyseur morphologique de textes latins : il est capable, si on lui donne une forme déclinée ou conjuguée, de trouver quel mot il faudra chercher dans le dictionnaire pour avoir sa traduction dans une autre langue, ses différents sens, et toutes les autres données que fournit habituellement un dictionnaire.

En pratique, il est utile surtout au professeur de latin, qui peut ainsi très rapidement, à partir d’un texte hors-manuel, distribuer à ses élèves un texte inédit avec son aide lexicale. Les élèves s’en servent souvent pour lire plus facilement le latin lorsque leurs connaissances lexicales et morphologiques sont encore insuffisantes.

Page web: [Collatinus](https://outils.biblissima.fr/fr/collatinus/){:target="_blank"}

[Télécharger la présentation Collatinus](/assets/doc/Collatinus.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }

---

## PALM
{: .mb-3 }

La plateforme PALM (Plateforme d’analyse linguistique médiévale) est destinée au traitement des textes médiévaux (MEDITEXT): il s'agit d'un système s'adressant moins aux philologues qu'aux historiens ou aux philosophes qui, désireux d'entreprendre des recherches lexicométriques ou sémantiques, se heurtent à l'absence d'une orthographe normalisée et à la variabilité tant géographique que chronologique des lexiques médiévaux.

Elle permet, par l'intermédiaire d'une annotation souple des textes, la semi-automatisation de la normalisation orthographique et de la lemmatisation des textes médiévaux en anglais, en français et en latin. 

Page web: [PALM](http://palm.huma-num.fr/PALM/){:target="_blank"}

[Télécharger la présentation PALM](/assets/doc/Palm.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }

---

## Pyrrha
{: .mb-3 }

Pyrrha est une simple Python Flask WebApp pour accélérer la post-correction de corpus lemmatisés et morpho-syntaxiquement tagués.

Page web: [Pyrrha](https://dh.chartes.psl.eu/pyrrha){:target="_blank"}

[Télécharger la présentation Pyrrha](/assets/doc/Pyrrha.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }

---

## spaCy
{: .mb-3 }

spaCy est une bibliothèque logicielle [Python](https://fr.wikipedia.org/wiki/Python_(langage)) de traitement automatique des langues (TAL/NLP). Elle permet d’implémenter différentes d’annotations linguistiques pour donner un aperçu de la structure grammaticale d'un texte (types de mots, parties du discours, relations des mots entre eux). Elle réalise la tokenisation, la lemmatisation, le POS-Tagging, parmi d’autres opérations avancées.

Page web: [spaCy](https://spacy.io/usage/spacy-101){:target="_blank"}
