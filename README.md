# BART - BiotransformAtion Reporting Tool

Version controlled spreadsheet template for reporting chemical contaminant biotransformation data.

![image](https://github.com/user-attachments/assets/216bb067-1ec6-4327-b2a5-fc6bab2dce39)

## Why do we need this tool?
There is a large amount of experimental data available on chemical contaminant biotransformations in the environment, but most of this data is stored in an inaccessible, non machine-readable format (e.g. behind paywalls, in PDFs). We aim to fix this by encouraging researchers to share their data in an open source, standardized format that can be easily used to upload the data into a open-source, freely available online software (e.g. [enviPath](https://envipath.org/)).

## About the template
This repository contains an empty version of the BiotransformAtion Reporting Tool (BART), and a filled-out version with data from the publication ([10.1021/acs.est.3c05506](https://pubs.acs.org/doi/full/10.1021/acs.est.3c05506)) as an example.

Empty template: https://github.com/FennerLabs/BART/blob/main/BART_AUTHOR_YEAR_PathwayName_Template.xlsx

Filled-out Example: https://github.com/FennerLabs/BART/blob/main/BART_FANG_2024_6-2FTNO_Example.xlsx

## Getting started

If you are researching chemical contaminant biotransformations and you wish to communicate your results in a FAIR, machine-readable, and standardized format, please submit a filled-out version of BART in the supporting information of your submitted manuscript.

The template contains multiple tabs, each of which are described below. There should be one template for each biotransformation pathway you wish to report.

### Description
After downloading the empty spreadsheet template, save a local version of the file with the first author last name, the year of publication, and the name of the parent compound or pathway in the format of "AUTHOR_YEAR_PathwayName.xlsx"

The Description tab contains additional guidance for fillng out the template as well as a table for providing your contact information and information about the publication with the biotransformation pathway. Here you should include an image of the pathway that you are reporting in the template where each compound in the pathway is clearly labeled.

### Compounds
You will need to fill out the Compounds tab before the other tabs are populated. In the Compounds tab, the names and [SMILES](https://en.wikipedia.org/wiki/Simplified_Molecular_Input_Line_Entry_System) of all compounds in the pathway should be listed. If you don't have the SMILES of your compounds, you can search for an online SMILES generator or used the SMILES generator on the [enviPath](https://envipath.org/) homepage. The column labeled "Type" indicates whether the compound your are entering is the parent compound (Parent) or a transformation product (TP). Only one parent compound can be listed per template, and up to 50 TPs can be reported.

### Connectivity
The Connectivity tab provides a tablular format for describing directional relationships across compounds in the reported pathway. The direction of the reported reaction will always go from reactant to product. You can pick each reactant and product from the drop down lists in the blue cells, and the SMILES for each compounds should automatically populate. If a reaction is suspected to consist of multiple enzymatic steps, you can designate this by adding a "multistep reaction" entry in the dropdown box provided in the "Multistep" column.

### Scenarios
Scnarios contain information on the environmental compartment in which the biotransformation pathway was measured. There are four types of Scenario tabs in this template. The Scenario_Sludge, Scenario_Soil, and Scenario_Water-Sediment tabs contain tables of specific parameters relevant for each type of environmental compartment. The Scenario_General tab contains all possible reportable parameters, and can be used to describe environmental compartments that do not fit into the Sludge, Soil, or Water-Sediment categories. These tables can help to guide data collection even before conducting biotransformation experiments.

### Kinetics_Confidence

## Special Cases
If your experimental design is not well represented by the template format, please visit the FAQ to see if we have a solution.

Otherwise, feel free to start a discussion thread and we will work to find a way to show your data.
