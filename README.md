# Jasbi, Jaggi, Frank (2018): Conceptual and prosodic cues assist disjunction acquisition

## Structure of the repo:

**1_raw_data**: contains the raw data used in the study. Files starting with "Providence" belong to our study 2: the annotation of disjunction in child directed speech in [the Providence corpus of CHILDES](http://phonbank.talkbank.org/browser/index.php?url=Eng-NA/Providence/). Other files belong to study 1. They record what we extracted from [childes-db](childes-db.stanford.edu). 

**2_processed_data** contains the dataframes used for study 1 plots. We obtain them by normalizing the frequency of the connectives by either the total number of words spoken by a speaker at a particular age (raw_normalized.csv) or the number of words in a particular speech act (bySpeechAct_normalized.csv).

**figs** contains the figures in the paper.

## Reproducability

To reproduce, please follow these steps:

1. Make sure you have [the R programming language](https://www.r-project.org/) and [R Studio](https://www.rstudio.com/) installed. This project used R Version 3.4.2 and R Studio Version 1.1.383.

2. Install the `cogsci2016` package. You can find [the pakcage and the instructions here](https://github.com/kemacdonald/cogsci2016).

3. Install the `childesr` package. [The github repo and instructions are here.](https://github.com/langcog/childesr)

4. Make sure the following R packages are installed: `png` (0.1.7), `grid` (3.4.2), `ggplot2` (2.2.1), `xtable` (1.8.2), `knitr` (1.18), `tidyverse` (1.1.1), `ggthemes` (3.4.0), `lubridate` (1.6.0), `magrittr` (1.5), `lme4` (1.1.14), `lmerTest` (2.0.33), `forcats` (0.2.0), `bootstrap` (2017.2), `jpeg` (0.1.8). If you want the packages installed at once use the following code: `install.packages(c("png", "grid", "ggplot2", "xtable", "knitr", "tidyverse", "ggthemes", "lubridate", "magrittr", "lme4", "lmerTest", "forcats", "bootstrap", "jpeg"))`.

5. Make sure you have an updated verison of LaTeX. You can install TeX by visiting the [LaTeX Project website](https://www.latex-project.org/get/).

6. Clone/download the repo here by clicking on the green button "Clone or download" on the right top of this page.

7. On your computer, open the main Rmarkdown file (JasbiJaggiFrank_cogsci2018.Rmd) and press Knit. 

Hopefully the Rmd file renders with no error and you get the pdf file (JasbiJaggiFrank_cogsci2018.pdf). If you see any errors/problems while reproducing our work or if you have any questions please do not hesitate to contact the first author.

