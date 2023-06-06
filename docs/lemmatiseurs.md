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

## Les lemmatiseurs et taggers

### TreeTagger
{: .mb-3 }

 The TreeTagger is a tool for annotating text with part-of-speech and lemma information. It was developed by Helmut Schmid in the TC project at the Institute for Computational Linguistics of the University of Stuttgart. The TreeTagger has been successfully used to tag German, English, French, Italian, Danish, Swedish, Norwegian, Dutch, Spanish, Bulgarian, Russian, Portuguese, Belarusian, Ukrainian, Galician, Greek, Chinese, Swahili, Slovak, Slovenian, Latin, Estonian, Polish, Persian, Romanian, Czech, Coptic and old French texts and is adaptable to other languages if a lexicon and a manually tagged training corpus are available. 

Page web: [TreeTagger](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/){:target="_blank"}

---

### Collatinus
{: .mb-3 }

Collatinus est à la fois un lemmatiseur et un analyseur morphologique de textes latins : il est capable, si on lui donne une forme déclinée ou conjuguée, de trouver quel mot il faudra chercher dans le dictionnaire pour avoir sa traduction dans une autre langue, ses différents sens, et toutes les autres données que fournit habituellement un dictionnaire.

En pratique, il est utile surtout au professeur de latin, qui peut ainsi très rapidement, à partir d’un texte hors-manuel, distribuer à ses élèves un texte inédit avec son aide lexicale. Les élèves s’en servent souvent pour lire plus facilement le latin lorsque leurs connaissances lexicales et morphologiques sont encore insuffisantes.

Page web: [Collatinus](https://outils.biblissima.fr/fr/collatinus/){:target="_blank"}

---

### spaCy
{: .mb-3 }

spaCy est une bibliothèque logicielle [Python](https://fr.wikipedia.org/wiki/Python_(langage)) de traitement automatique des langues (TAL/NLP). Elle permet d’implémenter différentes d’annotations linguistiques pour donner un aperçu de la structure grammaticale d'un texte (types de mots, parties du discours, relations des mots entre eux). Elle réalise la tokenisation, la lemmatisation, le POS-Tagging, parmi d’autres opérations avancées.

Page web: [spaCy](https://spacy.io/usage/spacy-101){:target="_blank"}

---

### Pie (et Deucalion/Flask Pie)
{: .mb-3 }

Pie is a language independant lemmatizer implemented in python and built for "variation-rich languages" which includes Latin. It's a deep learning tool that can be trained and retrained with data in TSV format. As of 2019, it seems to be one of the state-of-the-art lemmatizers in terms of results. It can be trained jointly on morphology, POS and lemmatization tasks. 

Page web: [Pie (et Deucalion/Flask Pie)](https://wiki.digitalclassicist.org/Deucalion_and_Pie_lemmatizers){:target="_blank"}

---

### StanfordNLP
{: .mb-3 }

StanfordNLP is a Python natural language analysis package. It contains tools, which can be used in a pipeline, to convert a string containing human language text into lists of sentences and words, to generate base forms of those words, their parts of speech and morphological features, and to give a syntactic structure dependency parse, which is designed to be parallel among more than 70 languages, using the Universal Dependencies formalism. In addition, it is able to call the CoreNLP Java package and inherits additonal functionality from there, such as constituency parsing, coreference resolution, and linguistic pattern matching.

Page web: [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/){:target="_blank"}

---

### WordNet (nltk)
{: .mb-3 }

WordNet® is a large lexical database of English. Nouns, verbs, adjectives and adverbs are grouped into sets of cognitive synonyms (synsets), each expressing a distinct concept. Synsets are interlinked by means of conceptual-semantic and lexical relations. The resulting network of meaningfully related words and concepts can be navigated with the browser. WordNet is also freely and publicly available for download. WordNet's structure makes it a useful tool for computational linguistics and natural language processing.

Page web: [WordNet](https://wordnet.princeton.edu/){:target="_blank"}

---

### TextBlob
{: .mb-3 }

TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

Page web: [TextBlob](https://textblob.readthedocs.io/en/dev/){:target="_blank"}

---

### MarMoT
{: .mb-3 }

MARMOT is a Python library for dealing with multimodal data consisting of both images and text. It does not require multimodal pretraining and it can deal with observations missing modalities. This repo is currently under construction and is in a very rough state; please feel free to reach out if you have any questions.

Page web: [MarMoT](https://github.com/patrickywu/MARMOT){:target="_blank"}

---

### FastText
{: .mb-3 }

FastText is an open-source, free, lightweight library that allows users to learn text representations and text classifiers. It works on standard, generic hardware. Models can later be reduced in size to even fit on mobile devices.

Page web: [FastText](https://fasttext.cc/){:target="_blank"}

---

### LGeRM
{: .mb-3 }

LGeRM (Lemmes Graphies et Règles Morphologiques, prononcer "elle germe"), est un lemmatiseur conçu pour gérer la variation graphique historique du français. Il a été initialement développé pour le moyen français (1330-1500) puis adapté au français du XVIe et XVIIe. Il est aussi capable de traiter du français moderne. 

Page web: [LGeRM](http://stella.atilf.fr/LGeRM/plateforme/){:target="_blank"}

---

### UDPipe
{: .mb-3 }

UDPipe is a trainable pipeline for tokenization, tagging, lemmatization and dependency parsing of CoNLL-U files. UDPipe is language-agnostic and can be trained given annotated data in CoNLL-U format. Trained models are provided for nearly all UD treebanks. UDPipe is available as a binary for Linux/Windows/OS X, as a library for C++, Python, Perl, Java, C#, and as a web service. Third-party R CRAN package also exists. 

Page web: [UDPipe](https://lindat.mff.cuni.cz/services/udpipe/){:target="_blank"}

---

### FreeLing
{: .mb-3 }

FreeLing is a C++ library providing language analysis functionalities (morphological analysis, named entity detection, PoS-tagging, parsing, Word Sense Disambiguation, Semantic Role Labelling, etc.) for a variety of languages (English, Spanish, Portuguese, Italian, French, German, Russian, Catalan, Galician, Croatian, Slovene, among others).

Page web: [FreeLing](https://nlp.lsi.upc.edu/freeling/index.php/){:target="_blank"}

---

### CLTK
{: .mb-3 }

The Classical Language Toolkit (CLTK) is a Python library offering natural language processing (NLP) for the languages of pre–modern Eurasia. Pre-configured pipelines are available for 19 languages.

Page web: [CLTK](http://cltk.org/){:target="_blank"}

## Les jeux de paramètres

Jeux de paramètres et modèles pour les langues médiévales, principalement pour le latin et l’ancien français:

- OMNIA (latin, en particulier latin médiéval ; TreeTagger)
- Lasla (latin ; Pie, via le modèle Deucalion latin + Collatinus)
- Achim Stein (anciens français ; TreeTagger)
- LatinCy (latin ; Spacy : [https://huggingface.co/latincy](https://huggingface.co/latincy){:target="_blank"}; [https://spacy.io/universe/project/latincy](https://spacy.io/universe/project/latincy){:target="_blank"}; [https://arxiv.org/abs/2305.04365](https://arxiv.org/abs/2305.04365){:target="_blank"})
- Deucalion (Ancien français ; [https://zenodo.org/record/3237455](https://zenodo.org/record/3237455){:target="_blank"}; lemmes issus du Tobler‑Lommatzsch +  POS issus de Cattex ; pour Pie)
- Middle High German (moyen haut allemand ; TreeTagger)
- PALM (TreeTagger)
- Latin pour TreeTagger (TreeTagger : [https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/){:target="_blank"})
- LiLa Lemma Bank (latin ; pas de logiciel spécifique : [https://lila-erc.eu/lodview/data/id/lemma/LemmaBank](https://lila-erc.eu/lodview/data/id/lemma/LemmaBank){:target="_blank"})
- Old French lemmatization (Ancien français ; TreeTagger : [https://github.com/CristinaGHolgado/old-french-lemmatization](https://github.com/CristinaGHolgado/old-french-lemmatization){:target="_blank"})
- eHumanities Desktop (latin ; MarMoT [https://www.texttechnologylab.org/applications/ehumanities-desktop/](https://www.texttechnologylab.org/applications/ehumanities-desktop/){:target="_blank"})
- Perseus TreeBank (latin ; [https://github.com/PerseusDL/treebank_data/tree/master/v2.0/Latin](https://github.com/PerseusDL/treebank_data/tree/master/v2.0/Latin){:target="_blank"})
- CLTK (plusieurs langues anciennes : latin ; vieil anglais ; moyen anglais ; moyen haut allemand ; etc. : [https://legacy.cltk.org/en/latest/index.html](https://legacy.cltk.org/en/latest/index.html){:target="_blank"}) 


## Les outils de post-traitement en lemmatisation

### Pyrrha
{: .mb-3 }

Pyrrha est une simple Python Flask WebApp pour accélérer la post-correction de corpus lemmatisés et morpho-syntaxiquement tagués.

Page web: [Pyrrha](https://dh.chartes.psl.eu/pyrrha){:target="_blank"}

[Télécharger la présentation Pyrrha](/assets/doc/Pyrrha.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }













