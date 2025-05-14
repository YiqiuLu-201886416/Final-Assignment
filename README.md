# Analysis of Household Deprivation and Crime In Leeds
## Overview of this study
The relationship between poverty and crime has always been a hot topic in society, and many people think that the poorer the area, the more crime will be, is this a stereotype or a reality?
In this study, we used 488 LSOAs in Leeds as the study area, using crime data from West Yorkshire Police in March 2025 and Households by deprivation dimensions from the 2021 census to discuss this topic. It is hoped that the results of the study will be helpful to policymakers or the public good.

The result of this study shows that the Spearman correlation coefficient of crime and poverty index shows a positive correlation (0.57). However, there is no clear linear relationship between the two in terms of non-spatial and spatial data distribution. The distribution of crime and poverty in some areas is not the same as some people's stereotypes or traditional perceptions. Therefore, it is recommended to adopt measures to improve local conditions according to the reality. At the same time, we should not stigmatize the relationship between crime and poverty.
## Data Source
This repository contains data below:

2025-03-west-Yorkshire-street.csv: Crime cases were recorded by West Yorkshire Police (March 2025)   https://data.police.uk/

Households by deprivation dimensions.csv: Household deprivation data from 2021 Census investigate.   https://www.ons.gov.uk/datasets/TS011/editions/2021/versions/6

Leeds.geojson: boundaries for Leeds LSOA in 2021.

Final_Project_201886416.ipynb: Analysis of Household Deprivation and Crime In Leeds Jupyter notebook.

More information is available in the Jupyter notebook.

## The aim of my codes

1.	Data cleaning and processing for merging deprivation and crime data.
   
2.	Utilizing Statistical Modelling including Spearman’s correlation coefficient and K-means clustering methods to see the different type of their relationship
   
3.	Using the modelling results to create spatial and non-spatial visualizations. Go further analysis of the variables.
## How to run the code:
1.	Open Google Colab: https://colab.research.google.com/. Click "File" → "Open notebook" → "GitHub" tab，Paste this repository URL https://github.com/YiqiuLu-201886416/Final-Assignment/blob/main/Final_Project_201886416.ipynb and select the notebook. 
 
2. If the GitHub or the link in the Jupyter notebook do not work: Download all files from this repository to your computer. Open Colab, click "File" then upload the notebook. For data files, click the folder icon on the left, then upload all CSV and geojson files.
 
3. Click Runtime and Run all cells. If you want to run step by step, remember to install and import the packages first.
   
## Reference

Office for National Statistics. 2021. Households by deprivation dimensions. Office for National Statistics. [Online]. [Accessed 10 May 2025]. Available from: https://www.ons.gov.uk/datasets/TS011/editions/2021/versions/6

Single Online Home National Digital Team. 2025. ASB Incidents, Crime and Outcomes. Single Online Home National Digital Team. [Online]. [Accessed 10 May 2025]. Available from: https://data.police.uk/
