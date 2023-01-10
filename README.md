# The temporal and spatial effects of indoor daylight on indoor microbiome in a hospital setting.
### Author: Man In (Rita) Lam
___
### Experiment Design
* Sample collection were performed at the University of Vermont Medical center (USA)
* 10 patient rooms were included in the study: 5 with regular window and blinds and 5 with electrochromic (EC) smart window. Detail of EC window can be found in our previous study: https://doi.org/10.1111/ina.13076
* Environmental and patient samples were collected a day before patient admission (T0), first day, second day and third day of patient admission
<img width="979" alt="Sample_Collection_workflow" src="https://user-images.githubusercontent.com/77307369/211134903-ba94f3f4-baa6-4200-9eb7-60a4fa475e5b.png">

### Data Analysis
Analysis consists of 4 parts which all codes can be found in folder **script**

* **PART 1**: Environmental Data Analysis
* **PART 2**: Total bacterial abundance analysis (If this file is too big to visualize on github, please clone this repository to your local desktop and open the html)
* **PART 3**  Data Analysis in R: Sequencing data (QIIME3) processing, Beta diversity analysis 
* **PART 4**  Alhpha diversity, EKSPAE pathogen relative abundance data analysis

#### Statistical Analysis workflow:
* Normality of data were assessed with Shapiro wilk test
* Variance of data were assesed with Levee's test

![statistical-test-Workflow](https://user-images.githubusercontent.com/77307369/211176212-a38fb79e-c0f5-420c-af05-903e18cb18f4.png)

#### Foleder **Raw data**
*  Raw sensor data used for  for environmental data analysis (Part1) can be found in folder "Environmental_Data"
*  qPCR_Data is used for PART 2 total bacteria abudnance analysis
* The "QIIME 2" folder in Raw_Data include all the files used for analysis in Part 3 
* The "shannon_index.csv", "Staphylococcus_abundance.csv", "Pseudomonas_abundance.csv" were used for analysis in Part 4. These file were generated in R from Part 3
