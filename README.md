# Jasbi, Jaggi, Frank (2018): Conceptual and prosodic cues assist disjunction acquisition

To reproduce, please clone the repo, open the main Rmarkdown file (JasbiJaggiFrank_cogsci2018.Rmd) and Knit. You should get the pdf file (JasbiJaggiFrank_cogsci2018.pdf). This project used R Version 3.4.2 and R Studio Version 1.1.383. If you see any problem while reproducing our work or if you have any questions please do not hesitate to contact the first author. 

## Structure of the repo:

**1_raw_data**: contains the raw data used in the study. Files starting with "Providence" belong to our study 2: the annotation of disjunction in child directed speech in [the Providence corpus of CHILDES](http://phonbank.talkbank.org/browser/index.php?url=Eng-NA/Providence/). Other files belong to study 1. They record what we extracted from [childes-db](childes-db.stanford.edu). 

**2_processed_data** contains the dataframes used for study 1 plots. We obtain them by normalizing the frequency of the connectives by either the total number of words spoken by a speaker at a particular age (raw_normalized.csv) or the number of words in a particular speech act (bySpeechAct_normalized.csv).

**figs** contains the figures in the paper.