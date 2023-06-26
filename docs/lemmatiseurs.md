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

Le TreeTagger est un outil permettant d'annoter des textes avec des informations sur les parties du discours et les lemmes. Il a été développé par Helmut Schmid dans le cadre du projet TC à l'Institut de linguistique informatique de l'université de Stuttgart. Le TreeTagger a été utilisé avec succès pour annoter des textes allemands, anglais, français, italiens, danois, suédois, norvégiens, néerlandais, espagnols, bulgares, russes, portugais, biélorusses, ukrainiens, galiciens, grecs, chinois, swahili, slovaques, slovènes, latins, estoniens, polonais, persans, roumains, tchèques, coptes et vieux français. Il est adaptable à d'autres langues si un lexique et un corpus d'entraînement étiqueté manuellement sont disponibles. 

Page web: [TreeTagger](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/){:target="_blank"}

---

### Collatinus
{: .mb-3 }

Collatinus est à la fois un lemmatiseur et un analyseur morphologique de textes latins : il est capable, si on lui donne une forme déclinée ou conjuguée, de trouver quel mot il faudra chercher dans le dictionnaire pour avoir sa traduction dans une autre langue, ses différents sens, et toutes les autres données que fournit habituellement un dictionnaire.

Bien que conçu initialement pour les professeurs de Latin, Collatinus s'est étoffé au fil des ans de plusieurs outils qui peuvent intéresser les médiévistes. En particulier, il permet de consulter différents dictionnaires, dont certains consacrés au Latin médiéval, en mode image pour certains et en plein texte pour d'autres (Du Cange et Köbler). Les différents dictionnaires ne donnant pas nécessairement les mêmes informations, il peut être pratique de passer de l'un à l'autre en un clic. D'autre part, le TextiColor peut s'avérer être un outil pratique pour repérer les coquilles dans l'OCR d'un texte latin. La scansion et l'accentuation sont aussi possibles avec Collatinus et peuvent être appliquées par exemple à l'étude de la poésie métrique ou rythmique. L'usage du cursus dans la prose peut aussi apporter des éléments de datation. On trouvera plus de détails ici: ["Lemmatiser avec Collatinus 3"](/assets/doc/Lemmatiser_avec_Collatinus3.pdf)


Page web: [Collatinus](https://outils.biblissima.fr/fr/collatinus/){:target="_blank"}

---

### spaCy
{: .mb-3 }

spaCy est une bibliothèque logicielle [Python](https://fr.wikipedia.org/wiki/Python_(langage)) de traitement automatique des langues (TAL/NLP). Elle permet d’implémenter différentes d’annotations linguistiques pour donner un aperçu de la structure grammaticale d'un texte (types de mots, parties du discours, relations des mots entre eux). Elle réalise la tokenisation, la lemmatisation, le POS-Tagging, parmi d’autres opérations avancées.

Page web: [spaCy](https://spacy.io/usage/spacy-101){:target="_blank"}

---

### Pie (et Deucalion/Flask Pie)
{: .mb-3 }

Pie est un lemmatiseur indépendant de la langue implémenté en python et conçu pour les "langues riches en variations", dont le latin. C'est un outil d'apprentissage profond qui peut être entraîné et réentraîné avec des données au format TSV. En 2019, il semble être l'un des lemmatiseurs de pointe en termes de résultats. Il peut être entraîné conjointement sur des tâches de morphologie, de POS et de lemmatisation. 

Page web: [Pie (et Deucalion/Flask Pie)](https://wiki.digitalclassicist.org/Deucalion_and_Pie_lemmatizers){:target="_blank"}

Additional links:
- [Pie Extended](https://github.com/hipster-philology/nlp-pie-taggers){:target="_blank"}
- [PIE: A Framework for Joint Learning of Sequence Labeling Tasks](https://github.com/emanjavacas/pie){:target="_blank"}
- [Deucalion](https://dh.chartes.psl.eu/deucalion/){:target="_blank"}

---

### StanfordNLP
{: .mb-3 }

StanfordNLP est un logiciel Python d'analyse du langage naturel. Il contient des outils, qui peuvent être utilisés dans un pipeline, pour convertir une chaîne contenant un texte en langage humain en listes de phrases et de mots, pour générer des formes de base de ces mots, leurs parties du discours et leurs caractéristiques morphologiques, et pour donner une analyse de la dépendance de la structure syntaxique, qui est conçue pour être parallèle parmi plus de 70 langues, en utilisant le formalisme des dépendances universelles. En outre, il est capable d'appeler le paquet Java CoreNLP et d'en hériter des fonctionnalités supplémentaires, telles que l'analyse syntaxique des constituants, la résolution des coréférences et l'appariement des modèles linguistiques.

Page web: [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/){:target="_blank"}

---

### WordNet (nltk)
{: .mb-3 }

WordNet® est une grande base de données lexicale de l'anglais. Les noms, les verbes, les adjectifs et les adverbes sont regroupés en ensembles de synonymes cognitifs (synsets), chacun exprimant un concept distinct. Les synsets sont reliés entre eux par des relations conceptuelles, sémantiques et lexicales. Le réseau de mots et de concepts significativement liés qui en résulte peut être parcouru à l'aide d'un navigateur. WordNet peut également être téléchargé gratuitement et publiquement. La structure de WordNet en fait un outil utile pour la linguistique informatique et le traitement du langage naturel.

Page web: [WordNet](https://wordnet.princeton.edu/){:target="_blank"}

---

### TextBlob
{: .mb-3 }

TextBlob est une bibliothèque Python (2 et 3) pour le traitement des données textuelles. Elle fournit une API simple permettant de se plonger dans des tâches courantes de traitement du langage naturel (NLP) telles que l'étiquetage des parties du discours, l'extraction de phrases nominales, l'analyse des sentiments, la classification, la traduction, et bien plus encore.

Page web: [TextBlob](https://textblob.readthedocs.io/en/dev/){:target="_blank"}

---

### MarMoT
{: .mb-3 }

MARMOT est une bibliothèque Python permettant de traiter des données multimodales composées à la fois d'images et de texte. Elle ne nécessite pas de pré-entraînement multimodal et peut traiter les observations de modalités manquantes. Ce repo est actuellement en construction et est dans un état très approximatif ; n'hésitez pas à nous contacter si vous avez des questions.

Page web: [MarMoT](https://github.com/patrickywu/MARMOT){:target="_blank"}

---

### FastText
{: .mb-3 }

FastText est une bibliothèque libre, gratuite et légère qui permet aux utilisateurs d'apprendre les représentations de texte et les classificateurs de texte. Elle fonctionne sur du matériel standard et générique. Les modèles peuvent être réduits par la suite pour tenir sur des appareils mobiles.

Page web: [FastText](https://fasttext.cc/){:target="_blank"}

---

### LGeRM
{: .mb-3 }

LGeRM (Lemmes Graphies et Règles Morphologiques, prononcer "elle germe"), est un lemmatiseur conçu pour gérer la variation graphique historique du français. Il a été initialement développé pour le moyen français (1330-1500) puis adapté au français du XVIe et XVIIe. Il est aussi capable de traiter du français moderne. 

Page web: [LGeRM](http://stella.atilf.fr/LGeRM/plateforme/){:target="_blank"}

---

### UDPipe
{: .mb-3 }

UDPipe est un pipeline entraînable pour la tokenisation, l'étiquetage, la lemmatisation et l'analyse des dépendances des fichiers CoNLL-U. UDPipe est indépendant de la langue et peut être entraîné à partir de données annotées au format CoNLL-U. Des modèles entraînés sont fournis pour presque toutes les banques d'arbres de l'UD. UDPipe est disponible sous forme de binaire pour Linux/Windows/OS X, de bibliothèque pour C++, Python, Perl, Java, C#, et de service web. Un paquet R CRAN tiers existe également. 

Page web: [UDPipe](https://lindat.mff.cuni.cz/services/udpipe/){:target="_blank"}

---

### FreeLing
{: .mb-3 }

FreeLing est une bibliothèque C++ offrant des fonctionnalités d'analyse linguistique (analyse morphologique, détection d'entités nommées, étiquetage PoS, analyse syntaxique, désambiguïsation du sens des mots, étiquetage sémantique des rôles, etc.) pour une variété de langues (anglais, espagnol, portugais, italien, français, allemand, russe, catalan, galicien, croate, slovène, entre autres).

Page web: [FreeLing](https://nlp.lsi.upc.edu/freeling/index.php/){:target="_blank"}

---

### CLTK
{: .mb-3 }

Le Classical Language Toolkit (CLTK) est une bibliothèque Python permettant le traitement du langage naturel (NLP) pour les langues de l'Eurasie pré-moderne. Des pipelines préconfigurés sont disponibles pour 19 langues.

Page web: [CLTK](http://cltk.org/){:target="_blank"}

## Les jeux de paramètres

Jeux de paramètres et modèles pour les langues médiévales, principalement pour le latin et l’ancien français:

### OMNIA
{: .mb-3 }

(latin, en particulier latin médiéval; TreeTagger) [https://glossaria.eu/lemmatisation/#page-content](https://glossaria.eu/lemmatisation/#page-content){:target="_blank"}

OMNIA a été élaboré pour être implementé au logiciel [TreeTagger](https://www.cis.lmu.de/~schmid/tools/TreeTagger/){:target="_blank"}, développé pour le marquage morphosyntaxique (_POS – Part of Speech_), mais qui permet également la lemmatisation. OMNIA propose à la fois les paramètres nécessaires à son utilisation avec des textes en latin médiéval, et les fichiers permettant de recréer ces paramètres.

Page web: [OMNIA](https://glossaria.eu/lemmatisation/#page-content){:target="_blank"}

---

### Lasla 
{: .mb-3 }

(latin; Pie, via le modèle Deucalion latin + Collatinus) [https://www.lasla.uliege.be/cms/c_8570393/fr/lasla-logiciels](https://www.lasla.uliege.be/cms/c_8570393/fr/lasla-logiciels){:target="_blank"}

---

### Achim Stein 
{: .mb-3 }

(anciens français; TreeTagger)

---

### LatinCy 
{: .mb-3 }

(latin; Spacy: [https://huggingface.co/latincy](https://huggingface.co/latincy){:target="_blank"}; [https://spacy.io/universe/project/latincy](https://spacy.io/universe/project/latincy){:target="_blank"}; [https://arxiv.org/abs/2305.04365](https://arxiv.org/abs/2305.04365){:target="_blank"})

---

### Deucalion 
{: .mb-3 }

(Ancien français; [https://zenodo.org/record/3237455](https://zenodo.org/record/3237455){:target="_blank"}; lemmes issus du Tobler‑Lommatzsch +  POS issus de Cattex; pour Pie)

---

### Middle High German 
{: .mb-3 }

(moyen haut allemand; TreeTagger)

---

### PALM 
{: .mb-3 }

(TreeTagger) [http://palm.huma-num.fr/PALM/](http://palm.huma-num.fr/PALM/){:target="_blank"}

La plateforme PALM (Plateforme d’analyse linguistique médiévale) est destinée au traitement des textes médiévaux (MEDITEXT): il s'agit d'un système s'adressant moins aux philologues qu'aux historiens ou aux philosophes qui, désireux d'entreprendre des recherches lexicométriques ou sémantiques, se heurtent à l'absence d'une orthographe normalisée et à la variabilité tant géographique que chronologique des lexiques médiévaux.

Elle permet, par l'intermédiaire d'une annotation souple des textes, la semi-automatisation de la normalisation orthographique et de la lemmatisation des textes médiévaux en anglais, en français et en latin. 

Page web: [PALM](http://palm.huma-num.fr/PALM/){:target="_blank"}

[Télécharger la présentation PALM](/assets/doc/Palm.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }

---

### Latin pour TreeTagger 
{: .mb-3 }

(TreeTagger: [https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/){:target="_blank"})

---

### LiLa Lemma Bank 
{: .mb-3 }

(latin; pas de logiciel spécifique: [https://lila-erc.eu/lodview/data/id/lemma/LemmaBank](https://lila-erc.eu/lodview/data/id/lemma/LemmaBank){:target="_blank"})

---

### Old French lemmatization 
{: .mb-3 }

(Ancien français; TreeTagger: [https://github.com/CristinaGHolgado/old-french-lemmatization](https://github.com/CristinaGHolgado/old-french-lemmatization){:target="_blank"})

---

### eHumanities Desktop 
{: .mb-3 }

(latin; MarMoT [https://www.texttechnologylab.org/applications/ehumanities-desktop/](https://www.texttechnologylab.org/applications/ehumanities-desktop/){:target="_blank"})

---

### Perseus TreeBank 
{: .mb-3 }

(latin; [https://github.com/PerseusDL/treebank_data/tree/master/v2.0/Latin](https://github.com/PerseusDL/treebank_data/tree/master/v2.0/Latin){:target="_blank"})

---

### CLTK
{: .mb-3 }

(plusieurs langues anciennes: latin; vieil anglais; moyen anglais; moyen haut allemand; etc.: [https://legacy.cltk.org/en/latest/index.html](https://legacy.cltk.org/en/latest/index.html){:target="_blank"}) 

## Les outils de post-traitement en lemmatisation

### Pyrrha
{: .mb-3 }

Pyrrha est une simple Python Flask WebApp pour accélérer la post-correction de corpus lemmatisés et morpho-syntaxiquement tagués.

Page web: [Pyrrha](https://dh.chartes.psl.eu/pyrrha){:target="_blank"}

[Télécharger la présentation Pyrrha](/assets/doc/Pyrrha.zip){: .btn .btn-green .fw-300 .text-grey-lt-000 }

