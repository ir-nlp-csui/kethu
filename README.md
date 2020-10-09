# Kethu: An Indonesian Constituency Treebank in the Penn Treebank Format
**(Kethu: Treebank "Constituency" Bahasa Indonesia dalam Format Penn Treebank)**

## Introduction

We revised and converted an Indonesian constituency treebank built by [**Dinakaramani et al. (2015)** ](https://github.com/famrashel/idn-treebank) to the Penn Treebank format, a de-facto standard in creating the constituency treebank. We named this treebank **Kethu**, a name of [a forest in Wonosobo](http://wiki-wisata.blogspot.com/2014/08/hutan-alas-kethu-wonogiri.html). Why a forest? Because the treebank contains parse trees, as the forest contains trees ;-) 

Characteristics of the treebank:
* Number of sentences: 1030
* Average sentence length: 27.4 tokens/sentence
* Genre: news in formal Indonesian


## Changelog
* 2020-10-08 v2.0
  * revised the POS tagging and syntactic annotation for compound words
  * revised the tokenization, POS tagging and syntactic annotation for predicate nominalization cases
  * revised the syntactic annotation for noun phrases containing numerical expression (especially QP)
  * changed the POS tag for 'Rp' and the similar tokens from SYM to NN

* 2019-09-01 v1.0
  * revised the bracketing format to PTB format
  * revised the POS tag set and adjusted the POS tagging
  * resolved missing punctuations, typo, incorrect reported speech annotation, etc.

## Contributors
* Ika Alfina and Jessica Naraiswari Arwidarasti


## Reference

The explanation on why and how we convert that treebank can be read in our paper:

* Jessica Naraiswari Arwidarasti, Ika Alfina, and Adila Alfa Krisnadhi. ["**Converting an Indonesian Constituency Treebank to the Penn Treebank Format**"](https://ieeexplore.ieee.org/abstract/document/9037723). In the Proceeding of The 2019 International Conference of Asian Language Processing (IALP 2019) in Shanghai, China, 15-17 November 2019. 

