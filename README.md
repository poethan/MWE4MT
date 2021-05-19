# MWE4MT
PhD Thesis MWE-MT related tools and sources.

This project includes many components:
1. the way to extract English-Chinese MWEs (based on MWEtools, MWEtoolkit, MP-aligner); extracted bilingual en-zh MWEs uploaded in this repository.
1.1 Files wmt18zhen_extractMWE.en and wmt18zhen_extractMWE.zh uploaded here are extracted bilingual English-Chinese MWEs without filtering. The filtered MWEs can be found with the following folder link [https://drive.google.com/drive/folders/19ZY0qkEgvE5p_fgi89UTR7PzBcDCpQdx?usp=sharing] free for research purpose (request needed to lifeng.han@adaptcentre.ie)

2. integrating MWEs into NMT in various languages.

3. the integration of Chinese radical into NMT

4. the German-English MWEs corpus and impacts for MT.
4.1 the extracted De-En bilingual MWEs (File "new5m.train.MPOutput_filtered085to100" contain the 3,159,226 parallel MWEs with original PoS information. File "./Copy_of_new5m.train.MPOutput_filtered085to100.en" and "Copy_of_new5m.train.MPOutput_filtered085to100.de" contain the extracted clean en and de MWEs respectively which are line be line aligned with each other. Folder: the same above link)

5. The radical4mt folder: NoDaLiDa2021 paper data. Chinese character decompositon in detailed levels and its application in NMT, plus bilingual Chinese-English MWEs with Chinese MWE terms decomposed in three levels. These corpus can be used as knowledge base for many NLP tasks, such as cross-lingual and multiliingual NLPs, bilingual terminology database.


...(more coming)
===


[Reference projects links:]

MWEtoolkit https://github.com/KWARC/mwetoolkit 

MP-aligner https://github.com/pmarcis/mp-aligner 

MWEtools https://github.com/M4t1ss/MWE-Tools

CHISE (CHaracter Information Service Environment) http://www.chise.org/

===

[Contributed projects:] 
https://github.com/alfredomg/ADAPT-MWE17

[If you use the corpus or the tools from MWE4MT git repositories, please kindly cite the corresponding papers from below:] 

Publications:

[I - MWE recognition:]

Moreau, Erwan, Alsulaimani, Ashjan, Maldonado, Alfredo , Han, Lifeng, Vogel, Carl  and Dutta Chowdhury, Koel (2018) Semantic reranking of CRF label sequences for verbal multiword expression identification. In: Markantonatou, Stella, Ramisch, Carlos , Savary, Agata and Vincze, Veronika , (eds.) Multiword expressions at length and in depth: Extended papers from the MWE 2017 workshop. Language Science Press, Berlin, pp. 177-207. ISBN 978-3-96110-124-5


Alfredo Maldonado, Lifeng Han, Erwan Moreau, Ashjan Alsulaimani, Koel Dutta Chowdhury, Carl Vogel and Qun Liu, Detection of Verbal Multi-Word Expressions via Conditional Random Fields with Syntactic Dependency Features and Semantic Re-Ranking, Proceedings of the 13th Workshop on Multiword Expressions (MWE 2017), Valencia, Spain, April 4, 2017, Stella Markantonatou, Carlos Ramisch, Agata Savary, and Veronika Vincze, Association for Computational Linguistics, 2017, 114-120


[II - character decomposition for MT:]

(Actural experiments done in 2017)
Han, Lifeng and Kuang, Shaohui (2018) Incorporating Chinese radicals into neural machine translation: deeper than character level. In: 30th European Summer School in Logic, Language and Information (ESSLLI 2018), 6-17 Aug 2018, Sofia, Bulgaria.



[III - MWE+MT:]


Han, Lifeng, Gareth, Jones  and Alan F., Smeaton  (2020) MultiMWE: building a multi-lingual multi-word expression (MWE) parallel
 corpora. In: 12th International Conference on Language Resources and Evaluation (LREC), 11-16 May, 2020, Marseille, France. (Virtual).

Lifeng Han, Gareth Jones, Alan Smeaton and Paolo Bolzoni. 2021. Chinese Character Decomposition for Neural MT with Multi-Word Expressions. 23rd Nordic Conference on Computational Linguistics (NoDaLiDa), forthcoming (accepted paper). Data available under the subfolder 'radical4mt'.



Ongoinging: and Further work

[IV - Linguistics Aware MWE+MT/MTE:]

"Unveil the Myth of Chinese Characters in Neural Machine Translation". Lifeng Han. 2020. Accepted to present in the "TCD Postgraduate Annual Conference - Abstract Presenation". Trinity College Dubin, Ireland. April 3-5th. Please see the file uploaded there <PG conference-Unveil the myth of Chinese characters in neural machine translation-Lifeng Han.pdf> and the conference web page http://trinityaiconference.com for detail and proper citation.
  


