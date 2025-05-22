# Wani_portfolio
 My selected data projects

# [Project 1: Bike User Behaviour Analysis](https://github.com/Wani2Y/Bike-user-behaviour-analysis-R)
Description: This project uses historical bike ride data from 2013 to 2023, to examine the different riding behaviours between subscribers and customers of Cyclistics, as well as the geospatial pattern of bike stations over the 10-year period.
As the total data set is fairly large (> 30 million rows), the scatter plots, U-test, Kruskal–Wallis test, and Wilcoxon signed-ranking test may take a long time to run. To speed up the computation, you may sample a subset of the total data for the same statistic tests. 
Raw data is more than 100 MB, so please visit the source website below to obtain the raw data.
The RMarkdown file is formatted to be viewed in RStudio console, and the knitted html report are for non-technical audience.

# [Project 2: Geospatial and Taxonomic Analysis on Alberta Roadkill](https://github.com/Wani2Y/Alberta-road-kill-R)
Description: This project uses reported road kill data in Alberta in 2020, to analyse which taxomoic groups are most impacted by vehicle traffic. The geospatial insights may inform policy making regarding the construction of wildlife corridor and the placement of animal crossing signs. Raw data belongs to the Alberta Wildlife Watch, and I obtained the raw data from the Alberta Open Data Portal.

# [Project 3: Geospatial Analysis of Pet licensing in Edmonton](https://github.com/Wani2Y/Edmonton-pet-license-distribution-R/tree/main)
Description: This project uses reported pet license data in Edmonton from 2019 - 2021, to examine whether more dog or cat owners live in various districts of Edmonton. This geospatial insights demonstrates some pet preference of local inhabitants, which may inform policies regarding registrations of pets and the needs of vet care.

# [Project 3: R Functional Genomic, Pathway Enrichment Analysis](https://github.com/Wani2Y/microarray-Gene_Ontology-R)
Description: This project uses genomic data from GEO published in peer-reviewed journal arbicle on mice infected by *Mycobacterium tuberculosis*, to explore which biological processes are overrepresented in asymptomtically infected mice.
I performed the initial exploratory data analysis to evaluate the quality of the cell data, which examine the validity and suitability of statistic tests chosen in the sourse article. Differential gene expression was used to isolated the significant data. As the source article sampled only lung tissues, all 134 samples are compared only to the Gene Ontology associated with lung. Instead of using the convenient enrichGO() function that could not select Gene Ontology for lung, I manually performed the analysis using Hypergeometric tests. Multiple testing is accounted for by computateons of the adjusted p-values. Instead of comparing across all groups, including controll and experimental groups, I performed pairwise calculation between any given two groups, to detect discrepencies on a more granular detail.
The RMarkdown file is formatted to be viewed in RStudio console. A knitted html report is available for users who prefer not to use RStudio.
