# The temporal and spatial effects of indoor daylight on indoor microbiome in a hospital setting.

___
### Experiment Description
Environmental and patient samples were collected in University of Vermont Medical Centers. Samples were collected in 5 patient rooms with EC window room, and 5 with regular patient rooms. 
<img width="937" alt="Screen Shot 2023-01-06 at 10 33 22 PM" src="https://user-images.githubusercontent.com/77307369/211134797-36c42ff6-937f-409a-aba5-b85874959285.png">

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
