# MADAR-TUN LINGUISTIC ANNOTATIONS

This repository provides a brief description and houses the linguistic annotations for the Tunisian part of the MADAR corpus (Bouamoret et al., 2018). These annotations were created during a research project outlined in the following paper, which has been accepted for presentation at the LDK conference scheduled to be held in Vienna in September 2023: 

* [Gugliotta, E. Dinarelli, M. (2023). *An Empirical Analysis of Task Relations in the Multi-Task Annotation of an Arabizi Corpus*](http://2023.ldk-conf.org/programme/)

The annotations presented here are the outcome of the same procedure used for the TArC corpus. For additional information and in-depth details, please refer to the TArC repository, or consult the following papers. The papers shed light on the methodology employed and provide a comprehensive understanding of the annotation process carried out for both the MADAR and TArC corpora.

* [Gugliotta, E. Dinarelli, M. (2022). Tarc: Tunisian arabish corpus first complete release. LREC2022.](https://aclanthology.org/2022.lrec-1.121.pdf)

* [Gugliotta, E. et al., (2020). Multi-Task Sequence Prediction For Tunisian Arabizi Multi-Level Annotation.](https://www.aclweb.org/anthology/2020.wanlp-1.16/)


### *Overview of DATA*

In this repository, you will find a collection of linguistic annotations, generated semi-automatically using a [Multi-Task Sequence Prediction System](https://gricad-gitlab.univ-grenoble-alpes.fr/dinarelm/tarc-multi-task-system): 

* Transliteration into Arabizi (*Arabish* level)
* Token classification: Tokens are categorized into three groups - *arabizi* (representing Arabic words written in Latin script), *foreign* (indicating foreign words), and *emotag* (denoting emoticons or smileys tags).
* Normalization in Arabic Script of the tokens classified as *arabizi* (following the CODA* convention [[1]](#1)).
* Tokenization of the *CODAfied* texts.
* Part-of-Speech tagging for the *arabizi* tokens.
* Lemmatization, in CODA* (Arabic-script)

MADAR-TUN-annotation numbers:

|**SENTENCES**|         |**LEMMA**|         
|:-----------:|:-------:|:-------:|
|   3,990     |         |  3,033  |         



<br />


### *License*

Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0)

<br />

### *Citation* 

Please cite this work as: 

````bibtex
@inproceedings{gugliotta-etal-wanlp2020, 
    title={An Empirical Analysis of Task Relations in the Multi-Task Annotation of an Arabizi Corpus}, 
    author={Gugliotta, Elisa and Dinarelli, Marco}, 
    booktitle={The 4th Conference on Language, Data and Knowledge (LDK 2023)}, 
    year={2023},
}

````


<br />

## References 

<a id="1">[1]<a/>
Habash, Nizar, et al. "Unified guidelines and resources for Arabic dialect orthography." Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018). 2018.
