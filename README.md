# Socio-Demographic Factors Influencing Child Marriage in Vietnam

## Brief Description
This project studies the socio-demographic determinants of child marriage within Vietnam, a practice where at least one individual in the union is under 18 years old. Child marriage is a significant global concern that undermines individual development and breaches human rights, particularly in regions such as Vietnam where it contributes to cycles of poverty, restricts access to education, and leads to negative health outcomes. Utilizing data from the 2020-2021 Multiple Indicator Cluster Surveys conducted by UNICEF and the General Statistics Office of Vietnam, this study applies multivariate binary logistic regression analysis to uncover socio-demographic factors influencing child marriage.

## Author Information and Contact
- **Name:** Holly Duong
- **Affiliation:** Denison University
- **Contact:** duong_h1@denison.edu / holly.n.duong@gmail.com

## Prerequisites
To run the analysis, you need to have R and the following libraries installed:
- **Software needed:** R version 4.3.2
- **Libraries/Packages:** `dplyr`, `ggplot2`, `plotly`, `car`, `sf`, `pROC`,  `arm`, and more detailed in code.

## Data
**Data Source:** The data for this study is sourced from the Multiple Indicator Cluster Surveys (MICS), conducted by UNICEF and the General Statistics Office (GSO) of Vietnam in 2021. For permission to access this data, please register on the [UNICEF MICS website](https://mics.unicef.org/surveys). 

**Citation:** General Statistics Office of Viet Nam and UNICEF (2021). Viet Nam Multiple Indicator Cluster Survey 2020-2021: Dataset. Ha Noi, Viet Nam: General Statistics Office.

**Key Variables:**
- Age at First Marriage
- Marital Status
- Area
- Region
- Ethnicity
- Education Level
- Wealth Indexes
- Access to Mass Media
- Health Insurance
- Contraceptive Use
- Awareness of HIV/AIDS

## Code
The project structure includes several folders and files:
- **Dataframes:** Folder containing exported CSV files of datasets for reference.
- **Raw Data:** Original dataset (encoded).
- **Visuals:** Folder containing exported figures and tables.
- **gadm41_VNM_shp:** Geodata for Vietnam map.
- **ChildMarriage.Rmd:** R Markdown file containing the complete analysis code.
- **ChildMarriage.html:** HTML export of the R Markdown file for easier viewing.

## Research Question and Hypotheses
**Research Question:** How do socio-demographic factors influence the prevalence of child marriage across different regions and ethnicities in Vietnam?

**Hypotheses:**
1. The likelihood of child marriage increases with lower levels of education and for individuals from financially disadvantaged backgrounds.
2. Child marriage prevalence varies significantly across regions and ethnic groups in Vietnam.
3. The impact of education on reducing child marriage is more pronounced in rural areas than in urban areas.

## Methods
The methodology involves multivariate binary logistic regression analysis to investigate the influence of various socio-demographic factors on the likelihood of child marriage in Vietnam.

## Additional Information
- Please ensure you have permission to access the data as specified by UNICEF and GSO. The usage of this data is restricted to the purposes expressed in the registration application form and prohibits redistribution or passing on to others in any form.
- Be mindful of the software and library versions to avoid compatibility issues.
