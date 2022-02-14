The content here is for the replication and extension of Thijssen et al (2020) that is included in this folder.

This project is a collaborative effort amongst the graduate student researchers at the University of Michigan and the original authors Dr. Sandra Thijssen, from the Radboud University, and Dr. Monica Luciana from the University of Minnesota.

The project is comprised of two steps: Stage 1 (preregistration) and Stage 2 (results + discussion).

For the Stage 1 preregistration, the \'91Stage 1\'92 folder includes two folders: Manuscript and Code. 
	- Manuscript: this folder includes the initial version of the manuscript that covers the Abstract, Introduction, Methods, and proposed Analyses. It also includes the effects from the original paper (and indirect effects 95% provided by the original authors) that will be used for the Aim 1 replication. Of note, the ACC FA values are only included as reference and are not being used, given the sig. changes in DWI preprocessing between release 1 and release 2.
	- Code: This folder includes the R Markdown code (and .html output) of template code that will be used for the final analyses. (1) Part1_AggregateData is used to compile the data that into a single .csv file used; (2) Part2_CreateVars_Descriptives performs exclusion criteria, variable creation/selection (consistent w/ original work) and puts it into a dataset; (3) fits the factors for our models and saves the individual scores for each subject; (4) uses fake data to demonstrate the code for the replication (Aim 1) and multiverse extension (Aim 2) that will be used with the full data.
