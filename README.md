# COVID-19 EFFECTS OF UNEMPLOYMENT IN MARGINALIZED COMMUNITIES
 
## Motivation of the Project
The period of Covid 19, especially the onset of the pandemic, was a tough time for all us. But it was harder for some of us than others. I wanted to explore this side of the pandemic, it’s effect on employment and how if effected the communities in **Norfolk County in Massachusetts**.

## Problem Statements:
- How did the increase in COVID-19 cases impact employment in Norfolk County in 2020-2021?

- Was there an increase in the unemployment claims as COVID-19 progressed in 2020-2021?

- What proportion of unemployment claims to the population for gender, race/ethnicity to understand how much such demographic groups were impacted?


## Data Sources

**Primary sources of data:**
1. *Weekly Unemployment Claims Data:*
    - Link to dataset: https://lmi.dua.eol.mass.gov/lmi/ClaimsData
    - This data is hosted on a website operated by the Department of Economic Research and was funded by a grant awarded by the U.S. Department of Labor's Employment and Training Administration.
    - Terms of Use: https://www.mass.gov/terms-of-use-policy
    - **Dataset Description:** Initial and continued weekly Unemployment Insurance claims by county. Includes claimant demographics (gender, race and ethnicity), industry, occupation, and education. 

2. *Labor and Unemployment Data:* 
    - Link to Dataset: https://lmi.dua.eol.mass.gov/LMI/LaborForceAndUnemployment#
    - This data is hosted on a website operated by the Department of Economic Research and was funded by a grant awarded by the U.S. Department of Labor's Employment and Training Administration.
    - Terms of Use: https://www.mass.gov/terms-of-use-policy
    - **Dataset Description:** Information on the labor force, employment, unemployment, and unemployment rates for each county in Massachusetts.
3. *John Hopkins University COVID-19 data:* 
    - Link to dataset: https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university
    - **Dataset Description:** The list of confirmed COVID cases by county.

**Secondary sources of data:**	
1. *Employment and Wages Data:*
    - Link to dataset: https://lmi.dua.eol.mass.gov/LMI/EmploymentAndWages#
    - This data is hosted on a website operated by the Department of Economic Research and was funded by a grant awarded by the U.S. Department of Labor's Employment and Training Administration.
    - Terms of Use: https://www.mass.gov/terms-of-use-policy
    - **Dataset Description:** Information on employment and wages is available by industry for counties in Massachusetts.
2. *Race & Ethnicity Demographic Data:*
    - Link to dataset: https://data.census.gov/table?g=0500000US25021&tid=ACSDT1Y2019.B03002
3. *Age and Sex Demographic Data:* 
    - Link to dataset: https://data.census.gov/table?g=0500000US25021&tid=ACSST5Y2019.S0101
4. *Education Demographic Data:* 
    - Link to dataset: https://data.census.gov/table?tid=ACSST5Y2020.S1501&g=0500000US25021

## Project Structure
```bash
data512_project_extension
├── documents
├── intermediate
├── processed
├── raw
├── results
├── source
├── LICENSE
└── README.md
 ```

### File Descriptions

The data is divided into three folders.

    raw: contains all the raw files from the data sources

    intermediate: data filtered for Norfolk county - filtering/cleaning done using Microsoft Excel

    processed: all outputs from Data Processing notebook go into this folder

Detailed descriptions of data folders can be found [here](https://github.com/anuhyabs/data512_project_extension/blob/main/documents/Data%20File%20Descriptions.pdf).

**documents:**:
- *Collective Analsyis.pdf*: Results of Project Part-1
- *Extension Plan.pdf*: Project plan for Part-2.
- *Presentation.pptx*: Presentation of results for Part-2.
- *Project Report.pdf*: Final Project report. 
- *Data file descriptions.pdf:* Detailed descriptions of files in the data folders.

**results**:
- *claims.png*: Visualization of unemployment claims in Norfolk County.
- *covid_vs_labor.png*: Visualization of COVID 19 confirmed cases vs Labor Force.
- *demographic.png*: Visualization of unemployment claims by demographic in Norfolk county.
- *claims_norfolk.png*: Visualization of unemployment claims in Norfolk County
- *Results.pdf*: Results of Statistic Analysis Tests

**source**:
- *Data Analysis.ipynb*: This notebook deals with analysis and visualizing the processed data from the Data Processing Notebook.
It also deals with application on statistical tests on the unemployment claims data.
- *Data Processing.ipynb*: This notebook deals with processing the raw/intermediate datasets to retain necessary information that can be used for further analysis and visualizations.

## Results

![results1](https://github.com/anuhyabs/data512_project_extension/blob/main/results/covid_vs_labor.png?raw=true)

- At the onset of the pandemic, during the first increase of COVID cases, it can be observed that there is a sharp increase in unemployment in the county.
- However, as the pandemic progresses and we see a rise in the cases, the unemployment in the county gradually decreases.
- From the above plots, we cannot say for sure that the impact on employment was solely due to covid cases but it does seem to point that in the face of unexpected disaster, the employment numbers do get impacted until economic support is provided by governments.

![results2](https://github.com/anuhyabs/data512_project_extension/blob/main/results/demographic.png?raw=true)

- Marginalized communities are impacted more at the onset of an unexpected disaster.
- Steps can be taken by the government in the face of such disasters to help communities beforehand. 
- These results help us understand what unemployment looks like during a pandemic and help plan the future much better. 
 
 [**Link to Statistical Test Results**](https://github.com/anuhyabs/data512_project_extension/blob/main/results/Results.pdf)

[**Link to Project Part 1**](https://github.com/anuhyabs/data512_project)