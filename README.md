# serotypesOfConcern
All code for manuscript Identifying a List of Salmonella Serotypes of Concern to Target for Reducing Risk of Salmonellosis  
DOI: https://doi.org/10.3389/fmicb.2024.1307563

KATZ_20230227_For Release.csv  
This file is the original raw data file from the CDC NORS dataset from the request made on 1/18/2023.

cleaning.Rmd  
Run this script first. It cleans KATZ_20230227_For Release.csv and will create dataset nors.csv for the analyses.

machineLearningApproach.Rmd  
Run this after cleaning.Rmd. It uses nors.csv and runs the AGNES analyses.

outlierApproach.Rmd  
Run this after cleaning.Rmd. It uses nors.csv and runs the outlier analyses.

table1.Rmd  
Run this after cleaning.Rmd. It will recreate Table 1 from the main article.

Email tatum.katz@usda.gov or katz.tatum@gmail.com with all questions.

Last updated: 03/12/2024
