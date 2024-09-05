# Text Mining & Search Project

This repository contains a project developed as part of *Text Mining & Search* course of the [Master's degree in Data Science](https://www.unimib.it/graduate/data-science),
University of Milano Bicocca.

# Description

The exponential proliferation of textual data in the digital era has presented both challenges and opportunities for extracting meaningful insights and knowledge. This project is dedicated to a comprehensive text mining procedure aimed at extracting valuable information from a vast collection of articles taken from WikiHow. 
Two main text mining tasks were accomplished in this project: 

* **Topic Modeling**: enables the automated discovery of latent topics within large collections of textual data by employing probabilistic models and statistical algorithms.
                      Two topic modeling techniques have been applied: LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation)

* **Text Summarization**: enables the automated summarization of a collection of textual data by employing extractive summarization algorithms, such as TextRank (TR) and LSA, as
                          well as two modified version of them designed on a paragraph basis (TRp and LSAp, where 'p' stands for 'paragraph').

# Repository structure

This repository is structured as follows:

```
├── Preprocessing                                        # Folder containing preprocessing operations and results
│   ├── Preprocessing.ipynb                               
│   └── wikiall_processed.csv
├── Report.pdf                                           # Detailed report of the project 
├── Text Summarization                                   # Folder containing summarization operations and results
│   ├── Summarization.ipynb
│   ├── summary_1k_red1.csv
│   ├── summary_1k_red2.csv
│   ├── summary_1k_red3.csv
│   └── wikisep_stats.csv
├── Topic Modeling                                       # Folder containing topic modeling operations and results
│   ├── LDA model
│   │   ├── bow_corpus.pkl
│   │   ├── dictionary12_.dict
│   │   ├── modello_lda(8_topics).lda
│   │   ├── modello_lda(8_topics).lda.expElogbeta.npy
│   │   ├── modello_lda(8_topics).lda.id2word
│   │   ├── modello_lda(8_topics).lda.state
│   │   ├── modello_lda12_save.lda
│   │   ├── modello_lda12_save.lda.expElogbeta.npy
│   │   ├── modello_lda12_save.lda.id2word
│   │   ├── modello_lda12_save.lda.state
│   │   └── risultati_metriche12.csv
│   ├── LSA model
│   │   ├── LSAmodel
│   │   └── LSAmodel.projection
│   └── Topic Modeling.ipynb
└── tms_data                                            # Folder containing the data implemented
    ├── wikihowAll.csv
    └── wikihowSep.csv
```

# Project replication

If one wants to replicate the project’s results from scratch, ‘Preprocessing.ipynb’ should be run first, then ‘Summarization.ipynb’ and ‘Topic Modeling.ipynb’ with no particular order. If one wants to replicate just the results of topic modeling or summarization, it is not needed to run ‘Preprocessing.ipynb’ first, instead ‘Summarization.ipynb’ and ‘Topic Modeling.ipynb’ can be run directly.
\
All the necessary packages are listed at the beginning of every notebook. 

