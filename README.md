# Summary

Middle-French ALTM (AUTOMATED Legal Texts Medieval) is a treebank of medieval legal French from Normandy.
Currently in contains one text, an extract from _Coutume, style et usage au temps des Échiquiers de Normandie_, dated 1425.


# Introduction
The text of the first ten chapters of _Coutume, style et usage au temps des Échiquiers de Normandie_ was digitised from the following edition:
A.-J. Marnier (ed). 1847. _Coutume, style et usage au temps des Échiquiers de Normandie_. Mémoires de la Société des antiquaires de Normandie. 2nd series, vol 8. Caen: A. Hardel, pp. 1-7.

The text was first annotated in PoS, lemmatised and automatically parsed as part of the Franco-German [MICLE project](https://www.unicaen.fr/projet_de_recherche/micle/) (2021-2024) led by Professor Pierre Larrivée (University of Caen) and Professor Cecilia Poletto (University of Frankfurt). An earlier version, annotated with [HT-CRISCO workflow](https://github.com/Corpus-Diachroniques-CRISCO/HT-CRISCO) incorporating the use of [HOPS parser](https://github.com/hopsparser/hopsparser), can be consulted on [CRISCO Lab's TXM server](https://txm-crisco.huma-num.fr/txm/) and via the [website](https://criscoht.unicaen.fr/).

The treebank currently contains **217 sentences** and **7,301 tokens**.

As part of [AUTOMATED project](https://www.unicaen.fr/projet_de_recherche/automated/) led by Professor Larrivée at the University of Caen (2023-2025), the text was reannotated with [BertForDeprel](https://github.com/kirianguiller/BertForDeprel) parser and manually corrected using bootstrapping methodology ([Peng et al 2022](https://hal.science/hal-03846834v1)) on [ArboratorGrew](https://arborator.grew.fr/#/) software.

Annotation in syntactic functions was conducted following the guidelines for Old French developed by the ([Profiterole project](https://github.com/UniversalDependencies/UD_Middle_French-PROFITEROLE)).

Wherever possible, lemmata used in the corpus are modern French or lemmata of the ([Dictionnaire du Moyen Français](http://zeus.atilf.fr/dmf/)).

Sentences written completely in Latin were excluded. If Latin words occur in French sentences, the token contains the tag Lang=la and is lemmatised with a Latin lemma.

Where morpological features are concerned, verbs and auxiliaries are annotated in verb forms (VerbForm): Inf (infinitive), Fin (conjugated) and Part (participle). Congujated forms are annotated in Person and Number. Pronouns are annotated in type (PronType: Dem for demonstrative, Ind for indefinite, Prs for personal and Rel for relative). Reflexive and possessive pronouns are also tagged (Reflexive=Yes and Poss=Yes). 

Please note that Middle_French-ALTM treebank is still under development and new material will be added to the collection in future UD releases. Please do not hesitate to contact us is you have any questions, suggestions or comments.

# Acknowledgments

This work was funded by ANR-DFG and Normandy Region grants and took place under the direction of Professor Pierre Larrivée (University of Caen). Mathieu Goux conducted initial PoS annotation and lemmatisation. Natasha Romanova is responsible for the revision of the annotation and for syntactic parsing. Théo Brillet assisted with syntactic annotation and annotated Latin tokens. Rayan Ziane and Khensa Daoudi provided technical support. 

## References

* (citation)


# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Genre: legal
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Romanova, Natalia; Ziane, Rayan; Daoudi, Khensa
Contributing: here
Contact: natalia.romanova@unicaen.fr
===============================================================================
</pre>
