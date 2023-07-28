# MADAR-TUN
2,000 Tunisian sentences of the MADAR corpus, semi-automatically annotated with several linguistic information (same procedure of TArC annotation, see the TArC repository for more information) 

## Linguistic information provided to the Tunisian-MADAR Corpus

This repository describes and contains the annotation provided to the Tunisian part of the MADAR corpus (Bouamoret al., 2018).
The annotation has been provided during a work described in the following paper (accepted for the LDK conference, to be held in Vienna in September 2023): 

* [An Empirical Analysis of Task Relations in the Multi-Task Annotation of an Arabizi Corpus, by Elisa Gugliotta, Marco Dinarelli](http://2023.ldk-conf.org/programme/)

The annotation are the result of the same procedure carried on for the TArC corpus. Please see the TArC repository, or the following paper for further details 

* [Gugliotta, E. Dinarelli, M. (2022). Tarc: Tunisian arabish corpus first complete release. LREC2022.](https://aclanthology.org/2022.lrec-1.121.pdf)

* [Gugliotta, E. et al., (2020). Multi-Task Sequence Prediction For Tunisian Arabizi Multi-Level Annotation.](https://www.aclweb.org/anthology/2020.wanlp-1.16/)


### *Overview of DATA*

In a nutshell, the data gathered in this repository you will find the following linguistic annotation levels, semi-automatically produced by a [Multi-Task Sequence Prediction System](https://gricad-gitlab.univ-grenoble-alpes.fr/dinarelm/tarc-multi-task-system): 

* Token classification into *arabizi*, *foreign* and *emotag*. 
* Encoding in Arabic Script of the tokens classified as *arabizi* (following the CODA* convention [[1]](#1)).
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
