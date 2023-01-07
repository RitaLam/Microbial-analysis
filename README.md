# The temporal and spatial effects of indoor daylight on indoor microbiome in a hospital setting.

___
### Experiment Design
* Sample collection were performed in University of Vermont Medical center (USA)
* 10 patient room were included in the study: 5 with regular window and blinds and 5 with electrochromic (EC) smart window
* Environmental and patient samples were collected a day before patient admission (T0), first day, second day and third day of patient admission
* 
<img width="979" alt="Sample_Collection_workflow" src="https://user-images.githubusercontent.com/77307369/211134903-ba94f3f4-baa6-4200-9eb7-60a4fa475e5b.png">

### Data Analysis
Analysis consists of 4 parts which all codes can be found in folder "script":

* **PART 1**: Environmental Data Analysis
* **PART 2**: Total bacterial abundance analysis
* **PART 3**  Data Analysis in R: Sequencing data (QIIME3) processing, Beta diversity analysis 
* **PART 4**  Alhpha diversity, EKSPAE pathogen relative abundance data analysis

NOTE: All raw data can be found in folder "Raw data"
*  Raw sensor data used for data for environmental data analysis can be found in folder "Environmental_Data"
*  qPCR_Data is used for PART 2 total bacteria abudnance
* The "QIIME 2" folder in Raw_Data include all the files used for analysis in Part 3 
* The "shannon_index.csv", "Staphylococcus_abundance.csv", "Pseudomonas_abundance.csv" were used for analysis in Part 4. These file were generated in R from Part 2
