# HELFI (Embargo 11 May 2020 or earlier; This repository is currently under construction.)
**HELFI: a Hebrew-Greek-Finnish Parallel Bible Corpus with Cross-Lingual Morpheme Alignment**:  An fine-grained and open morpheme-alignment between the most important 20th century Finnish Bible translation and the most relevant source texts.

## Parts of the HELFI Corpus

* [The Finnish 1933/1938 Bible Translation with Aika[media] copyrighted lemmas, morphology and cross-lingual morpheme alignment](https://github.com/amikael/HELFI/Finnish)
* [The Nestle 1904 Greek New Testament with Sandborg-Petersen's lemmas and morphology](https://github.com/amikael/HELFI/Greek) in a column-oriented file format containing token numbers for cross-lingual alignment
* [The Leningrad Codex Hebrew Bible (the Tanach) with the OSHB lemmas and morphology](https://github.com/amikael/HELFI/Hebrew) in a column-oriented file format containing token numbers for cross-lingual alignment
* [Supplementary material](https://github.com/amikael/HELFI/Supplements) 

This corpus is under several licenses that cover its copyrighted parts.  You must give appropriate credit, provide links to the licenses, and indicate if changes were made.  

* [How to cite or attribute the cross-lingual morpheme alignment](https://github.com/amikael/HELFI/CITING.md)
* [Parts that remain in the public domain or under their current restrictions](https://github.com/amikael/HELFI/LICENSES.md)

## The changes made to the public domain resources

### Changes to the Finnish 1933/1938 translation

Since 3,000 typographical mutations between the available printed and electronic copies of the translation were detected in 1996, the HELFI corpus contains the text curated by Anssi Yli-Jyrä in the Finnish Analytical Bible Concordance Project in 1996.  We are planning to review this work by consulting the physical master copy of the Finnish translation.   This is available at the National Archives of Finland, but no direct digital copies of the translation manuscript is known.    

### Changes to the files containing the Leningrad Codex of the Hebrew Bible

There are no content changes to the texts, but the XML file format of the OSHB has been replaced with a column-oriented format described in the HELFI paper.  This format contains HELFI-specific token numbers and fields and is helpful in communicating the way in which the texts have been aligned.

### Changes to the files containing the Nestle 1904 Edition of the Greek New Testament

There are no content changes to the texts, but the file format has been replaced with a column-oriented format described in the HELFI paper.  This format contains HELFI-specific token numbers and fields.  

## Acknowledgements

The dataset was created between 1991-2020 in two phases.  The **Product Development** phase (the Finnish Analytical Bible Concordance Project 1991-1997) was funded by Aika[media] Oy.  The Finnish lemmatisation has been supported by Aikamedia's collaboration with [Lingsoft Oy](https://www.lingsoft.fi/) and Professor Kimmo Koskenniemi at the University of Helsinki (UH).  The members of the editorial board were:  
* **Executive Editor** [Valtter Luoto](https://fi.wikipedia.org/wiki/Valtter_Luoto) (the publication of Bible Encyclopedias, visionary goals, concept design, and funding negotiation at Aika Oy), 
* **Editor in Chief** Lic.Th. [Matti Liljeqvist](https://fi.wikipedia.org/wiki/Matti_Liljeqvist) (alignment of the Hebrew Bible, alignment validation, product concept finalisation, proof reading, source language lexicography)
* M.A. [Anssi Yli-Jyrä](https://researchportal.helsinki.fi/fi/persons/anssi-yli-jyr%C3%A4) (technical lead, methodological innovation, alignment guidelines, natural language processing, text curation, morphological analysis, multi-word analysis, alignment editor, headword design, concordancing) 
* M.Th. Kari M. Räntila (alignment guidelines, alignment of the Greek New Testament, lexicon sketch for Greek)
* M.Th. [Arto Antturi](https://fi.wikipedia.org/wiki/Arto_Antturi) (concept design, license negotiations, methodological innovation, alignment guidelines)
* B.A. [Pekka Nieminen](http://kaannostoimisto-pekka-nieminen.onverkossa.fi/) (disambiguationof morphology and lemmas, named entity recognition and classification, coreference annotation, headword design).

The Product Development phase build a proprietary database, the Scaffold Corpus, that is not released.  However, we acknowledge the importance of having the following proprietary resources available to the Concordance Project in 1992-1997 as proprietary but important parts of the Scaffold Corpus:
* [Westminster Hebrew Morphology (WHM) and Lemma Database v.1.0](https://www.grovescenter.org/projects/westminster-hebrew-morphology/).  The analysis in this database had been perfected by scholars under the direction of Professor Alan Groves in the Westminster Theological Seminary, but the draft morphological analysis was done with the parser developed by Richard Whitaker (Claremont, Prince- ton Seminary).
* Paul Miller’s Greek New Testament Database from [the GRAMCORD Institute](http://www.gramcord.org/).

The **Resource Sharing** phase (2017-2020) has been enabled by the CC-BY license of Aikamedia and been supported by the University of Helsinki Faculty of Arts (decision N2/2017 for mobility support and 2018-2019 decisions for research assistance).  The purpose of this phase was to replace the propriate components in the Scaffold Corpus with resources that had fewer restriction.  The members of this phase were 
* **Principal Investigator** Docent Ph.D. Anssi Yli-Jyrä (license negotiations, supervision, the corpus documentation, data curation)
* M.Th. Josi Purhonen (free resource selection, data curation, resource switchover and its documentation, UNICODE translation)

# To-Do

1. The remaining licensing issues with the Hebrew Bible base text should be resolved.

1. The morphological glosses of extractors (%inflection, %mod, etc.) should be reviewed and corrected where necessary.

1. The Hebrew text needs non-numerical Strong's lemmas or the lemmas used in the Finnish Analytical Bible Concordance.

1. The codes and the alignment guidelines in the corpus need to be documented.

1. The inter-annotation agreement on the alignment and morphological disambiguation should be estimated.

# Contact

The HELFI corpus is maintained by Anssi Yli-Jyrä (_firstname.yli-jyra@helsinki.fi_).
