# MetaHOPE: Metaphor Translation Evaluation Framework Investigating Open-Source LLMs and State-of-the-Art Neural Translation Models

# Abstract:
In this work, we propose MetaHOPE, an error severity-aware annotation framework for evaluating metaphor translations. 
Metaphors present challenges for machine translation (MT) and natural language understanding and processing (NLU, NLP), because it presents the features of semantic complexity, contextual dependency, and cultural embeddedness that can lead to ambiguity issues for NLP models (Li et al., 2024; Karakanta et al., 2025).

Using this MetaHOPE framework, the study investigates:
RQ-1: What types of metaphor translation errors are produced by different MT systems?
RQ-2: How do the frequency and severity of errors vary across systems and translation directions (EN-ZH and ZH-EN)?

To investigate how state-of-the-art NLP models perform on translating metaphors, we select three representative systems, i.e., GoogleMT, GPT5.4, and Hunyuan-7b (Zheng et al., 2025) as Neural MT (NMT) models, LLMs and SOTA WMT system. We used two human-annotated metaphor corpora, including VUAMC (Steen et al., 2010) and PSUCMC (Lu & Wang, 2017) for English-to-Chinese and Chinese-to-English translation purposes.

The original corpora we used are monolingual, where we carried out error annotation using the MetaHOPE framework, and also produced the human post-edited gold reference for bilingual use as a new resource.

Preliminary results show that our human annotators’ agreement levels for [GoogleMT, GPT-5.4, Hunyuan-LLM-7B] are [0.536, 0.726, 0.333] for Pearson’s correlation, and [76.9%, 70.8%, 61.5%] for exact agreement. Metaphor translation errors are demonstrated as the main cause of translation errors, occupying [91.7%, 93.8%, 61.8%] error ratios of the three translation systems, respectively. We further qualitatively clustered the MT errors and interesting phenomena into distinct categories.

We believe the MetaHOPE evaluation framework for metaphor translation annotation, the parallel corpora resources, and the error analysis on SOTA automatic translation models can be useful and shed some light on the field of metaphor translation study.


# This repository includes:
- MetaHOPE annotation manual
- metaphor-related words (MRW) alingment manual
- Extracted / formated source files
- human annotations with error severity on corpus used : English to Chinese; Chinese to English. 
- Bilingual corpus created
  


# Reference / please cite the following work if you use the materials shared from this project

Jianghui Liang, and Lifeng Han. 2026. MetaHOPE: Metaphor Translation Evaluation Framework Investigating Open-Source LLMs and State-of-the-Art Neural Translation Models. forthcoming: ICNLSP-2026: 9th International Conference on Natural Language and Speech Processing

 DOI: 10.13140/RG.2.2.14337.42084
LicenseCC BY-NC 4.0

[paper-preprint](https://www.researchgate.net/publication/407161850_MetaHOPE_Metaphor_Translation_Evaluation_Framework_Investigating_Open-Source_LLMs_and_State-of-the-Art_Neural_Translation_Models)
[metaHOPE-paper-on-this-git](https://github.com/aaronlifenghan/MetaHOPE/blob/main/MetaHOPE.pdf)
