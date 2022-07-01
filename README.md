# ABCD_EnvBrainPubert_ReplicateExtend

The content here is for the replication and extension of **Thijssen et al (2020)** that is included in this folder.

This project is a collaborative effort amongst six graduate student researchers and Professor, Dr Daniel Keating, from the University of Michigan, Postdoctoral student, Dr. Ka Ip,  at Yale University, Professor at the University, and the original author Dr. Sandra Thijssen, from the Radboud University, and Dr. Monica Luciana from the University of Minnesota.

The project is comprised of two steps: Stage 1 (preregistration) and Stage 2 (results + discussion). Stage 1 is preregistered on the Open Science Framework at: 

## Stage 1 preregistration 
the Stage 1 folder includes two folders: Manuscript and Code. 

  + *Manuscript*: this folder includes the initial version of the manuscript that covers the Abstract, Introduction, Methods, and proposed Analyses. It also includes the effects from the original paper (and indirect effects 95% provided by the original authors) that will be used for the Aim 1 replication. 
    + Of note, the ACC FA values are only included as reference and are not being used, given the sig. changes in DWI preprocessing between release 1 and release 2.
  +	*Code*: This folder includes the R Markdown code (and .html output) of template code that will be used for the final analyses. Each of the for steps have self-contained explanations of steps within the file and the associated methods/packages linked 
    + (1) Part1_AggregateData is used to compile the data that into a single .csv file used; 
    + (2) Part2_CreateVars_Descriptives performs exclusion criteria, variable creation/selection (consistent w/ original work) and puts it into a dataset; 
    + (3) Part3_ExtrractFactorScores fits the factors for our models and saves the individual scores for each subject;
    + (4) Part4_MediationSpecificationCurve uses fake data to demonstrate the code for the replication (Aim 1) and multiverse extension (Aim 2) that will be used with the full data.

The associated Stage 1 preregistration for Aim 1 can be found at: https://doi.org/10.17605/OSF.IO/GXK96

## Stage 2 Analyses/Results
the Stage 2 folder includes the code folder with the R .rmd and .html files. There were only minor changes between
the preregistered and final code used. By placing the R code within the same folder where the archived data is downloaded, e.g. ABCDStudyNDA_1182451, the script was tested on Mac and Window systems. The R version used for each test >v3.8   
+	*Code*: 
  + (1) Part1_AggregateData a typo for two brain measures were updated; 
  + (2) Part2_CreateVars_Descriptives; 
  + (3) Part3_ExtrractFactorScores;
  + (4) Part4_MediationSpecificationCurve: uses real data as opposed to fake data in preregistration



For information regarding this content please contact demidenko.michael@gmail.com


