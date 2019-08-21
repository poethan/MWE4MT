# MWE4MT
PhD Thesis MWE-MT related tools and sources.

This project includes many components, such as:
1. the way to extract English-Chinese MWEs (based on MWEtools, MWEtoolkit, MP-aligner) 
2. integrating MWEs into NMT
3. the integration of Chinese radical into NMT
4. the German-English MWEs corpus and results for MT.

...(more coming)


[Reference projects links:]

MWEtoolkit https://github.com/KWARC/mwetoolkit 

MP-aligner https://github.com/pmarcis/mp-aligner 

MWEtools https://github.com/M4t1ss/MWE-Tools



[Contributed project:] 
https://github.com/alfredomg/ADAPT-MWE17

[If you use the corpus or the tools, please kindly cite the corresponding papers from below:] 

Publication:

[I - MWE recognition:]

@incollection{moreau:hal-01930987,
  TITLE = {{Semantic reranking of CRF label sequences for verbal multiword expression identification}},
  AUTHOR = {Moreau, Erwan and Alsulaimani, Ashjan and Maldonado, Alfredo and Han, Lifeng and Vogel, Carl and Dutta Chowdhury, Koel},
  URL = {https://hal.archives-ouvertes.fr/hal-01930987},
  BOOKTITLE = {{Multiword expressions at length and in depth: Extended papers from the MWE 2017 workshop}},
  PAGES = {177 - 207},
  YEAR = {2018},
  DOI = {10.5281/zenodo.1469559},
  PDF = {https://hal.archives-ouvertes.fr/hal-01930987/file/PMWE2-semantic-reranking.pdf},
  HAL_ID = {hal-01930987},
  HAL_VERSION = {v1},
}

@inproceedings{maldonadoHanMoreau2017detection,
  title={Detection of Verbal Multi-Word Expressions via Conditional Random Fields with Syntactic Dependency Features and Semantic Re-Ranking},
  author={Maldonado, Alfredo and Han, Lifeng and Moreau, Erwan and Alsulaimani, Ashjan and Chowdhury, Koel Dutta and Vogel, Carl and Liu, Qun},
  booktitle={The 13th Workshop on Multiword Expressions @ EACL 2017},
  year={2017},
  organization={ACL}
}



[II - MT:]

@article{HanKuang2018NMT,
  author    = {Lifeng Han and Shaohui Kuang},
  title     = {Incorperating Chinese Radicals Into Neural Machine Translation: Deeper Than
               Character Level},
  journal   = {Proceedings of ESSLLI-2018},
  volume    = {abs/1805.01565},
  year      = {2018},
  url       = {http://arxiv.org/abs/1805.01565},
  archivePrefix = {arXiv},
  eprint    = {1805.01565},
  timestamp = {Mon, 13 Aug 2018 16:48:29 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1805-01565},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}

[III - MWE+MT/MTE:]
forthcoming

