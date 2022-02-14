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
    + (3) fits the factors for our models and saves the individual scores for each subject;
    + (4) uses fake data to demonstrate the code for the replication (Aim 1) and multiverse extension (Aim 2) that will be used with the full data.


## Stage 2 Analyses/Results
The code will be added to a subsequent folder with the associated results upon completion of analyses.



For information regarding this content please contact demidenm@umich.edu


