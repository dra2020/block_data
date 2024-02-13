# block_data
This repository references Block-level demographic and election data used in Dave's Redistricting App, as CSV files.
The files are organized by geography (e.g. 2020_Geography (Shapes)) and then by state.

YOU ARE RESPONSIBLE FOR READING AND UNDERSTANDING THE LICENSES FOR THIS DATA, INCLUDING INDIVIDUAL DATASET LICENSES IF ANY.

YOU AGREE NOT TO SELL ANY OF THIS DATA UNDER ANY CIRCUMSTANCES.

## 2020 Geography
Within each state folder are two Markdown (.md) files, referring to demographic data and election data, respectively. Each markdown file contains a link to a zip archive to download. Each archive contains a CSV file with the data, a LICENSE file and a README file with other details. For all states, a link to the Block shapes (on the Census Bureau's site) is provided in the README.

The census files contain 2010 and 2020 demographic data from the decennial census, both total population and voting age population, and 2018, 2019 and 2020 American Community Survey (5-year) population estimates and citizen voting age population (CVAP) estimates. All of the data is orginally from the U.S. Census Bureau.

We have election data through 2021 for each state and 2022 data for some states.
* Most election data was obtained from Voting and Election Science Team (https://dataverse.harvard.edu/dataverse/electionscience). This data is available under the Creative Commons Attribution license (CC BY 4.0, https://creativecommons.org/licenses/by/4.0/).
* Please see About Data (https://davesredistricting.org/maps#aboutdata) for complete information on data sources. Also, each download specifies the data source and license information.

## CVAP Data
The Census Bureau provides CVAP estimates with the 5-year ACS data, but those estimates don't have the calculations for the race combinations (e.g. "Black Alone or in combination with other races"). The CVAP data only includes these two-race combinations: "Native and White", "Asian and White", "Black and White", "Native and Black", plus "Remainder of Two or More Races". We estimate the combinations by adding those two-race combinations, but leaving out the remainder, which tends to underestimate the race combinations.

## Disaggregation
Data from the 2020 decennial census is presented by the Census Bureau at the censu block level, therefore that data requires not disaggreation.
All other datasets were disaggregated to 2020 census blocks by Dave's Redistricting using the method by Voting and Election Science Team (Amos, Brian, 2021, "2020 Census Block Crosswalk Data", https://doi.org/10.7910/DVN/T9VMJO, Harvard Dataverse, V2), except 2019 ACS data was disaggregated by VEST and 2020 CVAP data was disaggregated by Redistricting Data Hub (https://redistrictingdatahub.org/data/about-our-data/american-community-survey/#cvap).

Except for the 2020 CVAP data, VEST's and our disaggregation allocated remainders using the Hare Quota (https://en.wikipedia.org/wiki/Largest_remainder_method), with 2020 Total Population as the factor determining the weight of each block within the precinct or block group.

