# Kethu: An Indonesian Constituency Treebank in the Penn Treebank Format
**(Kethu: Treebank "Constituency" Bahasa Indonesia dalam Format Penn Treebank)**

## Summary

We revised and converted an Indonesian constituency treebank built by [**Dinakaramani et al. (2015)** ](https://github.com/famrashel/idn-treebank) to the Penn Treebank format, a de-facto standard in creating the constituency treebank. We named this treebank **Kethu**, a name of [a forest in Wonosobo](http://wiki-wisata.blogspot.com/2014/08/hutan-alas-kethu-wonogiri.html). Why a forest? Because the treebank contains parse trees, as the forest contains trees ;-) 

Characteristics of the treebank:
* Number of sentences: 1030
* Average sentence length: 27.4 tokens/sentence
* Genre: news in formal Indonesian

## Dataset Split
Since this dataset is very small, we recommend using ten-fold cross-validation.

## Changelog
* 2020-10-27 v2.0
  * revised the POS tagging and syntactic annotation for compound words
  * revised the tokenization, POS tagging and syntactic annotation for predicate nominalization cases
  * revised the syntactic annotation for noun phrases containing numerical expression (especially QP)
  * changed the POS tag for 'Rp' and the similar tokens from SYM to NN

* 2019-09-01 v1.0
  * converted the bracketing format to the PTB format
  * revised the POS tag set and adjusted the POS tags to the PTB tagset
  * resolved missing punctuations, typo, incorrect reported speech annotation, etc.

## Acknowledgments

* The original constituency treebank was built with manual annotation by [Arawinda Dinakaramani, Fam Rashel, Andry Luthfi, and Ruli Manurung](https://github.com/famrashel/idn-treebank) at Faculty of Computer Science, Universitas Indonesia in 2015.
* The Kethu v1.0 was built in 2019 by Jessica Naraiswari Arwidarasti and Ika Alfina, as the output of Jessica's undergraduate thesis project.
* The Kethu v2.0 was built in 2020 by Jessica Naraiswari Arwidarasti and Ika Alfina, as the output of Jessica's "Studi Mandiri" project.

## References

Please cite the following papers if you use this treebank for your project/publication:
* Jessica Naraiswari Arwidarasti, Ika Alfina, and Adila Alfa Krisnadhi. ["**Adjusting Indonesian Multiwords Expression Annotation to the Penn Treebank Format**"](https://ieeexplore.ieee.org/document/9310479). In the Proceeding of The 2020 International Conference of Asian Language Processing (IALP) 2020 in Kuala Lumpur, Malaysia, 4-6 Desember 2020 _(Online)_. 

* Jessica Naraiswari Arwidarasti, Ika Alfina, and Adila Alfa Krisnadhi. ["**Converting an Indonesian Constituency Treebank to the Penn Treebank Format**"](https://ieeexplore.ieee.org/abstract/document/9037723). In the Proceeding of The 2019 International Conference of Asian Language Processing (IALP)  2019 in Shanghai, China, 15-17 November 2019. 

## Licence
You can use this dataset for free. You don't need our permission to use it. Please cite our paper if your work uses our data in your publication.
Please note that you are not allowed to create a copy of this dataset and share it publicly in your own repository without our permission.

## Contact
ika.alfina [at] cs.ui.ac.id
