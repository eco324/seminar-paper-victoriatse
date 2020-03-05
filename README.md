# README
This repository contains all the code necessary to reproduce the analysis for my seminar project xxx prepared for Susan Sayre's ECO 324 at Smith College during the Spring 2020 semester. This README document provides an outline orienting the user to the material contained in the repository. 

*After reading this file, your audience should understand the structure of your project. As with the other documents in this sample repository, notes in italics (like this one) document their use and should be removed from your versions before submission.*

The root directory of the project contains the following files:

1. `data_appendix.Rmd` contains descriptions and documentation of the raw data files used in the project along with code for reading the files into R and dataframe summaries created using the `summarytools` package. It also contains a description of the steps along with the code used to transform the raw data files into the final variables used in the regression analysis. Each variable used in a regression is documented in the file, which also creates a summary of the final data frame.

3. `yourlastname-paper.Rmd` produces the final paper. Code to run the regressions and create the output is embedded in the document. If you choose to write your paper in Word or google docs instead of RMarkdown, you will need to either include the code needed to generate your regressions and the output used in your paper in your data appendix or create a separate file. You should still include the paper in your repository. If you are using google docs, you will only be able to include the PDF of the paper but with Word you can include the paper itself.

These files create and/or draw on material stored in the following folders:

- `raw-data/` contains all the original, unaltered files used in the analysis. These files are documented in the data_appendix.
  
- `importable-data/` contains importable versions (if necessary) whose creation is described in the data appendix. *Delete this entry from this Rmd file if you did not need to create importable data files.*
   
- `processed-data/` contains intermediate datasets created during the project. *For this project, you should store your datasets that are created by the the data appendix files in this folder, so that the code in each .Rmd document can run independently of the other files. In a typical research project, it would be more common to have the code in a separate .R file and source it in each document where it is needed. If you are familiar with this workflow and want to adapt these templates to use that, you are welcome to do so provided you check with me first.*

- `output/` contains other files created by the code. *This includes the dataframe summaries created in the data appendix and could include figures or tables that need to be used in multiple .Rmd files.*
