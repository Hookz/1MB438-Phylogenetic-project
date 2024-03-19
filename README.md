# About the project

This group project forms a part of the course [1MB438](https://www.uu.se/en/study/course?query=1MB438) at Uppsala University. The project was defined as follows:
> In this project you will perform a complete phylogenetic analysis from gathering the data to interpreting the results. You will work in groups of 2 or 3. Each small group will work on one of eight questions (see below). You will try to answer a biological question by analyzing two mitochondrial genes: 
> * cytB, coding for the Cytochrome B protein (CYB), which is a heme-binding protein involved in the electron transport of the mitochondrial respiratory chain.
> * 16S, ribosomal 16S gene, a non-coding structual rRNA gene.

The question selected was: *Are salamanders more closely related to frogs than to lizards?*

## Project files
All of the project files are located in the DATA directory and split into subdirectories.

The directories [Frogs](DATA/Frogs), [Lizards](DATA/Lizards), [Salamanders](DATA/Salamanders), and [Outgroup](DATA/Outgroup) contain the original cytB and 16S genes obtained from full mitochondrial sequences. 

The directory [MSA](DATA/MSA) contains the results from multiple-sequence alignment performed on [16S](DATA/MSA/16S) and [cytB](DATA/MSA/cytB) genes, in their respective subdirectories. Additionally, the parsimony scores are reported in [MSA_parsimony_scores](DATA/MSA/MSA_parsimony_scores). 

The directory [iqtree](DATA/iqtree) contains the results from IQ-TREE performed on [16S](DATA/iqtree/16S) and [cytB](DATA/iqtree/cytB) genes, in their respective subdirectories.

The directory [beauti](DATA/beauti) contains the results from the *Bayesian Evolutionary Analysis Utility* (BEAUti) performed on the *cytB* gene.  

## Used software
The software used to run this project was [beagle-lib](https://github.com/beagle-dev/beagle-lib) and [BEAST](https://github.com/beast-dev/beast-mcmc). Both packages are not necessary to be downloaded to see the results and as such are not directly linked in this repository. 

## Outcomes
The visualisations of individual results are available as PDF files in the [visualisations directory](visualisations).

The final presentation is available [under this link](presentation/Project_phylogeny.pptx).

## Group composition
This project was completed in a three-person group consisting of me, Ditte Jacobs, and Jacob Siljebo. The work was done collaboratively on a remote server at [Uppsala Univeristy's Biology Education Centre](https://www.ibg.uu.se/?languageId=1). This is a final version that was presented in October 2023 and made available here for posteriority.
