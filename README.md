# serotypesOfConcern
All code for manuscript Identifying a List of Salmonella Serotypes of Concern to Target for Reducing Risk of Salmonellosis

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

Email tatum.katz@usda.gov with all questions.
