# Wani_portfolio
 My selected data projects

# [Project 1: Google Data Analytic Capstone](https://github.com/Wani2Y/R_Data_Analytics/tree/main/Google_Data_Analytic_Capstone)
Description: This project uses historical bike ride data from 2013 to 2023, to examine the different riding behaviours between subscribers and customers of Cyclistics.
As the total data set is fairly large (> 30 million rows), the scatter plots, U-test, Kruskal–Wallis test, and Wilcoxon signed-ranking test may take a long time to run. To speed up the computation, you may sample a subset of the total data for the statistic tests. I did not because I was super stubborn :P
Raw data is more than 100 MB, so please visit the source website below to obtain the raw data.
The RMarkdown file is formatted to be viewed in RStudio console, and the knitted html report are for non-technical audience.

# [Project 2: R Functional Genomic, Pathway Enrichment Analysis](https://github.com/Wani2Y/R_Bioinformatics/tree/main/GO%20Enrichment%20analysis%20TB%20mice)
Description: This project uses genomic data from GEO published in peer-reviewed journal arbicle on mice infected by $\textit{Mycobacterium tuberculosis}$, to explore which biological processes are overrepresented in asymptomtically infected mice.
As the source article sampled only lung tissues, all 134 samples are compared only to the Gene Ontology associated with lung. Instead of using the convenient enrichGO() function that could not select Gene Ontology for lung, I performed the analysis using Hypergeometric tests. Multiple testing is accounted for by computateons of the adjusted p-values.
The RMarkdown file is formatted to be viewed in RStudio console. A knitted html report will be uploaded in the near future.
