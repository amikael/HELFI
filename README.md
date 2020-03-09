# HELFI (Embargo 11 May 2020 or earlier; This repository is currently under construction.)
**HELFI: a Hebrew-Greek-Finnish Parallel Bible Corpus with Cross-Lingual Morpheme Alignment**:  An fine-grained and open morpheme-alignment between the most important 20th century Finnish Bible translation and the most relevant source texts.

## Parts of the HELFI Corpus

* [The Finnish 1933/1938 Bible Translation with Aika[media] copyrighted lemmas, morphology and cross-lingual morpheme alignment](https://github.com/amikael/HELFI/Finnish)
* [The Nestle 1904 Greek New Testament with Sandborg-Petersen's lemmas and morphology](https://github.com/amikael/HELFI/Greek) in a column-oriented file format containing token numbers for cross-lingual alignment
* [The Leningrad Codex Hebrew Bible (the Tanach) with the OSHB lemmas and morphology](https://github.com/amikael/HELFI/Hebrew) in a column-oriented file format containing token numbers for cross-lingual alignment
* [Supplementary material](https://github.com/amikael/HELFI/Supplements) 

This corpus is under three licenses that cover its copyrighted parts.  You must give appropriate credit, provide links to the licenses, and indicate if changes were made.  The easiest way to mention these is by citing the HELFI corpus paper (Yli-Jyrä et al. 2020), see below.

## How To Cite or Attribute the Corpus

The HELFI corpus and the license information of its third-party components can be cited through this reference:

> Anssi Yli-Jyrä, Josi Purhonen, Matti Liljeqvist, Arto Antturi, Pekka Nieminen, Kari M. Räntilä, Valtter Luoto, authors. (2020).  HELFI: a Hebrew-Greek-Finnish Parallel Bible Corpus with Cross-Lingual Morpheme Alignment  _Proceedings of the Twelfth International Conference on Language Resources and Evaluation (LREC 2020)_, Marseille, France, 11-16 May 2020. European Language Resources Association (ELRA).

The HELFI corpus is a combination of copyrighted and public domain resources. The above article (Yli-Jyrä et al 2020) contains the attributions for the following copyrighted components of the HELFI:

1. The Strong's lemma and morphology data of the Hebrew Bible are licensed under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). For attribution purposes, credit the Open Scriptures Hebrew Bible Project (https://hb.openscriptures.org/).

1. The Finnish morphology and lemmatisation are licensed under a [Creative Commons Attribution NonCommercial 4.0 International license](https://creativecommons.org/licenses/by-nc/4.0/). For attribution purposes, credit the Finnish Analytical Bible Concordance Project of Aika[media] Oy.  **TENTATIVE**

1. All the alignment data of the HELFI corpus are licenced under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). For attribution purposes, credit the Finnish Analytical Bible Concordance Project of Aika[media] Oy.  

The Finnish Analytical Bible Concordance Project of Aika[media] Oy can be cited as:

  > Valtter Luoto, Matti Liljeqvist, Anssi Yli-Jyrä, Arto Antturi, Pekka Nieminen, Kari M. Räntilä, editors. (1997). _Iso Raamatun Sanahakemisto (The Finnish Analytical Bible Concordance)_, volumes 1–2. Raamatun Tietokirja, Aika Oy Kristilliset Kirjat, Keuruu, Finland.

As a whole, the HELFI corpus is restricted by these three licenses while some of its parts remain in the public domain when distributed separately.

## Parts that Remain in the Public Domain

1. The Finnish 1933/1938 Bible translation.  The electronic copy produced by the HELFI project is now released and is in **the public domain**.  

1. The Leningrad Codex of the Hebrew Bible, the Tanakh.  The HELFI corpus contains the electronic version known as [Westminster Leningrad Codex WLC 4.20](http://www.tanach.us/Pages/TEIHeader.xml).  This XML version is maintained by the J. Alan Groves Center for Advanced Biblical Research. **All biblical Hebrew text, in any format, may be viewed or copied without restriction** according to the [License](http://www.tanach.us/License.html).

1. Eberhard Nestle (1904, 1913): _H Kainη ∆iaθηkη (Greek New Testament); Text with Critical Apparatus_. British and Foreign Bible Society.  The first edition of 1904, and a reprinting from 1913 are available throug the Internet Archive.  [The electronic version edited by Diego Renato dos Santos](https://sites.google.com/site/nestle1904/) is identified by http://sites.google.com/site/nestle1904/ and is in the **public domain**.

1. Morphological parsing and lemmatization of the Nestle 1904 edition made by Dr. Ulrik Sandborg-Petersen of Emergence Consult and Aalborg University, Denmark, and released into the **public domain**. Available at https://github.com/biblicalhumanities/Nestle1904.

## Indication of Changes Made to the Public Domain Resources

### Changes to the Finnish 1933/1938 Translation

Since 3,000 typographical mutations between the available printed and electronic copies of the translation were detected in 1996, the HELFI corpus contains the text curated by Anssi Yli-Jyrä in the Finnish Analytical Bible Concordance Project in 1996.  We are planning to review this work by consulting the physical master copy of the Finnish translation.   This is available at the National Archives of Finland, but no direct digital copies of the translation manuscript is known.    

### Changes to the files containing the Westminster Leningrad Codex of the Hebrew Bible

There are no content changes to the texts, but the XML file format has been replaced with a column-oriented format described in the HELFI paper.  This format contains HELFI-specific token numbers and fields.

### Changes to the files containing the Nestle 1904 Edition of the Greek New Testament

There are no content changes to the texts, but the file format has been replaced with a column-oriented format described in the HELFI paper.  This format contains HELFI-specific token numbers and fields.  

## Acknowledgements

The dataset was created between 1991-2020 in two phases.  The **Product Development** phase (the Finnish Analytical Bible Concordance Project 1991-1997) was funded by Aika[media] Oy.  The Finnish lemmatisation has been supported by Aikamedia's collaboration with [Lingsoft Oy](https://www.lingsoft.fi/) and Professor Kimmo Koskenniemi at the University of Helsinki (UH).  The members of the editorial board were:  
* **Executive Editor** [Valtter Luoto](https://fi.wikipedia.org/wiki/Valtter_Luoto) (the publication of Bible Encyclopedias, visionary goals, concept design, and funding negotiation at Aika Oy), 
* **Editor in Chief** Lic.Th. [Matti Liljeqvist](https://fi.wikipedia.org/wiki/Matti_Liljeqvist) (alignment of the Hebrew Bible, alignment validation, product concept finalisation, canity checks, source language lexicography)
* M.A. [Anssi Yli-Jyrä](https://researchportal.helsinki.fi/fi/persons/anssi-yli-jyr%C3%A4) (technical lead, methodological innovation, alignment guidelines, natural language processing, text curation, morphological analysis, multi-word analysis, alignment editor, headword design, concordancing) 
* M.Th. Kari M. Räntila (alignment guidelines, alignment of the Greek New Testament)
* M.Th. [Arto Antturi](https://fi.wikipedia.org/wiki/Arto_Antturi) (concept design, license negotiations, methodological innovation, alignment guidelines)
* B.A. [Pekka Nieminen](http://kaannostoimisto-pekka-nieminen.onverkossa.fi/) (disambiguationof morphology and lemmas, named entity recognition and classification, coreference annotation, headword design).

The Product Development phase build a proprietary database, the Scaffold Corpus, that is not released.  However, we acknowledge the importance of having the following proprietary resources available to the Concordance Project in 1992-1997 as proprietary but important parts of the Scaffold Corpus:
* [Westminster Hebrew Morphology (WHM) and Lemma Database v.1.0](https://www.grovescenter.org/projects/westminster-hebrew-morphology/).  The analysis in this database had been perfected by scholars under the direction of Professor Alan Groves in the Westminster Theological Seminary, but the draft morphological analysis was done with the parser developed by Richard Whitaker (Claremont, Prince- ton Seminary).
* Paul Miller’s Greek New Testament Database from [the GRAMCORD Institute](http://www.gramcord.org/).

The **Resource Sharing** phase (2017-2020) has been enabled by the CC-BY license of Aikamedia and been supported by the University of Helsinki Faculty of Arts (decision N2/2017 for mobility support and 2018-2019 decisions for research assistance).  The purpose of this phase was to replace the propriate components in the Scaffold Corpus with resources that had fewer restriction.  The members of this phase were 
* **Principal Investigator** Docent Ph.D. Anssi Yli-Jyrä (license negotiations, supervision, the corpus documentation, data curation)
* M.Th. Josi Purhonen (free resource selection, data curation, resource switchover and its documentation, UNICODE translation)


# Contact

The HELFI corpus is maintained by Anssi Yli-Jyrä (_firstname.yli-jyra@helsinki.fi_).
