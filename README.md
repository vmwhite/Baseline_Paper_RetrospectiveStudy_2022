# Baseline Paper Retrospective Study 2022 Code Repository

This code repository contains the R code and intermediate analysis used to report the computational results for the paper: 

Zhang, A. et al. A retrospective observational study of law enforcement encounters for opioid-related overdoses and future arrests, incarceration, and overdoses: highlighting the need to break the vicious cycle. (2022)

Baseline_Paper_Analysis_Code.Rmd is the R file used to run the analysis. It was created using R version 3.6.0 and was run with the following pacakge versions:
* MASS version 7.3-51.4
* Readxl verson 1.3.1
* xlsx version 0.6.1
* dplyr version 0.8.3
* lmtest version 0.9-37
* BSDA version 1.2.0
* DescTools version 0.99.32
* ggplot2 version 3.3.0
* Hmisc version 4.4-0
* aod version 1.3.1
* tidyverse version 1.3.0
* exactRankTests version 0.8-32
* qqplotr version 0.0.5


The main R file generates the following three excel files:
* Table1_Demographics_All.xlsx
* Table2_BaselineStatistics_Group1.xlsx
* Table3_BaselineStatistics_Group2.xlsx

The VBACodeforTables.txt file was used to reformat the three excel files into an alternative format that more closely resembles how the tables are reported in the published paper. 

Since the input data files are not able to be stored here, the html file, Baseline_Paper_Analysis_Code.nb.html, shows the generated statistical tests completed by the r code, that is then reported in the paper. To view the file simply download it and open the file using any web browser (e.g., Chrome).

If you have any questions regarding the analysis conducted, please reach out to Veronica White at vmwhite@wisc.edu. 

