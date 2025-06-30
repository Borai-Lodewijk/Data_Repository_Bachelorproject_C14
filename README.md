README - Research Data Documentation
====================================

Project Title: The co-association of free-living nematodes and wood ants	
Project Number: C14
Researcher(s): Borai Lodewijk 
Supervisor: Thomas Blankers
Institution/Organization: Institute for Biodiversity and Ecosystem Dynamics - University of Amsterdam
Date of Data Collection: [02/04/2025 - 17/04/2025]  
Date of README Creation: [30/06/2025]  
Version: 1.0
Contact Information: www.bjr99@hotmail.nl

Summary
-------
This dataset was collected as part of the Bachelor research project "C14 The co-association of free-living nematodes and wood ants"
This data was collected to gain insight in the microbial community present within and near Formica ant nest mounds.
For more detail, refer to the accompanying research report.

Data overview
-------
File formats: [.txt, .xlsx, .html, .tsv, .R]
Location of metadata: present in each excel file as worksheet "metadata"

Contents
--------
1. Raw_Field_Data_Bachelorproject_Ant_Microbiome.xlsx
 - Description: all raw field data that was collected during the sampling period
 - Sheets:
     • Metadata - contains information on all types of data collected
     • Raw_field_data – contains all data collected during the sampling period

2.  Borai_2 (File folder)
 - Description: Raw output from sequencing using Oxford nanopore sequencing method (MinION Mk1B MN33532)

3. Borai_TB_Nanoclass_Documentation.txt
 - Description: contains the script used for the ubunto Nanoclass 2 workflow
 - see https://doi.org/10.5281/zenodo.14264107  for more detail on usage

4. Nanoclass2 workflow output (File folder)
 - Description: Contains the step by step output from the Nanoclass 2 workflow
  - see https://doi.org/10.5281/zenodo.14264107  for more detail on usage

5. otu-table.tsv
 -Description: Final output of the nanoclass 2 workflow, containing all BLAST results linked to the used Barcodes

6. R-DATA.xlxs
 - Description: Modified version of the otu-table, making the file usable for the R-studio script
 
7. Bachelorproject data analysis.R
 -Description: The R-studio script for the data-analysis and creation of graphs.
 
8. Jitse_nest_data.xlxs
 -Description: Previously found Formica nest location from a study conducted in 2024 by Jitse Kramer, included as the files are currently not published in another format
