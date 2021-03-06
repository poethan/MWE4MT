# MWE4MT
PhD Thesis MWE-MT related tools and sources.

This project includes many components, such as:
1. the way to extract English-Chinese MWEs (based on MWEtools, MWEtoolkit, MP-aligner); extracted bilingual en-zh MWEs uploaded in this repository.
1.1 Files wmt18zhen_extractMWE.en and wmt18zhen_extractMWE.zh uploaded here are extracted bilingual English-Chinese MWEs without filtering. The filtered MWEs can be found with the following folder link [https://drive.google.com/drive/folders/19ZY0qkEgvE5p_fgi89UTR7PzBcDCpQdx?usp=sharing] free for research purpose (request needed to lifeng.han@adaptcentre.ie)

2. integrating MWEs into NMT in various languages.
3. the integration of Chinese radical into NMT
4. the German-English MWEs corpus and impacts for MT.
4.1 the extracted De-En bilingual MWEs (File "new5m.train.MPOutput_filtered085to100" contain the 3,159,226 parallel MWEs with original PoS information. File "./Copy_of_new5m.train.MPOutput_filtered085to100.en" and "Copy_of_new5m.train.MPOutput_filtered085to100.de" contain the extracted clean en and de MWEs respectively which are line be line aligned with each other. Folder: the same above link)

...(more coming)
===


[Reference projects links:]

MWEtoolkit https://github.com/KWARC/mwetoolkit 

MP-aligner https://github.com/pmarcis/mp-aligner 

MWEtools https://github.com/M4t1ss/MWE-Tools


===

[Contributed project:] 
https://github.com/alfredomg/ADAPT-MWE17

[If you use the corpus or the tools, please kindly cite the corresponding papers from below:] 

Publications:

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

(Actural experiments done in 2017)
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

[III - MWE+MT:]


@InProceedings{han-jones-smeaton:2020:LREC,
  author    = {Han, Lifeng  and  Jones, Gareth  and  Smeaton, Alan},
  title     = {MultiMWE: Building a Multi-lingual Multi-Word Expression (MWE) Parallel Corpora},
  booktitle      = {Proceedings of The 12th Language Resources and Evaluation Conference},
  month          = {May},
  year           = {2020},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {2970--2979},
  abstract  = {Multi-word expressions (MWEs) are a hot topic in research in natural language processing (NLP), including topics such as MWE detection, MWE decomposition, and research investigating the exploitation of MWEs in other NLP fields such as Machine Translation. However, the availability of bilingual or multi-lingual MWE corpora is very limited. The only bilingual MWE corpora that we are aware of is from the PARSEME (PARSing and Multi-word Expressions) EU Project. This is a small collection of only 871 pairs of English-German MWEs. In this paper, we present multi-lingual and bilingual MWE corpora that we have extracted from root parallel corpora. Our collections are 3,159,226 and 143,042 bilingual MWE pairs for German-English and Chinese-English respectively after filtering. We examine the quality of these extracted bilingual MWEs in MT experiments. Our initial experiments applying MWEs in MT show improved translation performances on MWE terms in qualitative analysis and better general evaluation scores in quantitative analysis, on both German-English and Chinese-English language pairs. We follow a standard experimental pipeline to create our MultiMWE corpora which are available online. Researchers can use this free corpus for their own models or use them in a knowledge base as model features.},
  url       = { https://www.aclweb.org/anthology/2020.lrec-1.363 }
}


Ongoinging: Further work

[IV - Linguistics Aware MWE+MT/MTE:]

"Unveil the Myth of Chinese Characters in Neural Machine Translation". Lifeng Han. 2020. Accepted to present in the "TCD Postgraduate Annual Conference - Abstract Presenation". Trinity College Dubin, Ireland. April 3-5th. Please see the file uploaded there <PG conference-Unveil the myth of Chinese characters in neural machine translation-Lifeng Han.pdf> and the conference web page http://trinityaiconference.com for detail and proper citation.
  
  

